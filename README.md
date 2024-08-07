# user-flow-segmentation
#### The data follows the new user - who installed and opened the game for the first time - from 28-10-2023 to 03-11-2023 and follows their activities for the next 7 days. The data columns are described as follows:

1. event_name - Describes the event name.
2. day_time - Records the time when the event_name was recorded.
3. user - Identifies each user.
4. day0 - Records the time when the user first opened the game.
5. day_diff - Calculated as day_time - day0, representing the time difference.
6. level - Indicates the level of event_name in the game.
7. version - Represents the version of the app that the user is using.
8. mode_game - Describes the mode of the game (e.g., session start or user engagement).
9. win - Records whether the user won (1) or lost (0) in the game_end event.
