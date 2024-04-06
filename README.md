# DataOrientedQuestManager

This DataOrientedQuestManager is a highly efficient, template-based quest management system designed for games, capable of handling a fixed number of quests concurrently. It provides functionality to add, start, update, and complete quests, with each quest's progress tracked through item counts and statuses. Optimized for performance, it uses fixed-size arrays to minimize dynamic memory allocation and offers methods like StartAllQuests to operate on multiple quests simultaneously. Ideal for developers looking for a scalable, data-oriented approach to quest management in their games.



## StartQuestSystem
Description: Activates the quest management system, allowing quests to be started and managed.

## StartAllQuests
Description: Initiates all added quests that have non-empty IDs, marking them as started.

## StartQuest
Description: Begins the quest with the specified ID, if it exists, by setting its status to started.

## AddQuest
Description: Adds a new quest to the system with a given ID and the number of required items to complete it.

## IncrementQuestItemCount
Description: Increases the item count for a specified quest, only if the quest is already started.

## CompleteQuest
Description: Marks the quest with the given ID as completed, changing its status accordingly.

## IsCompleted
Description: Determines whether the quest identified by the given ID has been completed.

## UpdateAllQuests
Description: Goes through all quests, marking them as completed if their item count requirement is met.
