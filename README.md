# Rucksack-Stats-Extension

## Demo Setup:

- Demo contain custom items so there is custome item factory binder with new custome items:
ItemFactory.Bind<UnityEquippableItemWithStatsDefinition, UnityEquippableItemInstanceWithStats>();
ItemFactory.Bind<ConsumablePotionItemDefinition, ConsumablePotionItemInstance>();

- Character contain UnityCharacterStats and for temporary stats TemporaryStatsHandler component.

- UI have temporary stats UI if we drtink potion of get buff we have visual representation of this.

Rucksack Manager have tab "Stats" for creating stats

## How we create database?

In project window right mouse click > Create > V7G > Stats > Stats Database

## There is two new custome item definitin:

UnityEquippableItemWithStatsDefinition - For equippment with stats, wen we equip item we get new stats

ConsumablePotionItemDefinition - this work like potion and have duration. Stats are handle by Temporary stats handler and after duration time removed from stats.
