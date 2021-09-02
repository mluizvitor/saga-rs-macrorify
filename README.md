# About

This macro was created to auto rematch SaGaRS quests. It need activation of **Normal AUTO** or **Full Power AUTO**. 

Now the 'SaGa RS - Auto Farm / Expedition' macro has speed modes for slow and fast connections and it is possible to choose the amount of Stamina Potions to be used. When starting the macro, you will be asked how many potions you want to use and the speed of the checks.

Just click "Play Mode" in the Macrorify menu, enter the SaGa Re;univerSe. Enter the desired battle and start it manually. You can also use this macro in Expeditions.

This macro supports auto-stop. The macro will stop when it fails to detect a battle or when a connection error occurs after several checks. When you are not in a battle or an expedition, please remember to click the pause '⏸' button so that the macro doesn't suddenly stop and you don't lose a reputation point.

-----

As battles can vary in duration, this macro reads specific elements and responds as they match, rather than clicking nonstop.

During battle, you will see some glows in random places near the center and a little more in the upper corner of the screen. This is expected behavior and is intended to prevent screen shutdown. It is recommended to place the Macrorify Player at the top left of your screen and not cover the battle menu button.

# Other functions

* Supports connection errors (Auto retry);

* Supports Game Over / Defeat (Auto retry);

* Supports Expeditions (Auto Return);

* Supports various confirmations;

* Supports Stamina recovery (It will use event potions first, then normal potions);

* Prevents screen-off;

* Supports auto-stop;

* Uses random point click area to prevent macro detection.

* Compatible with resolutions 720p and 1080p; And 9:16, 9:18 and 9:19 screen aspect ratios. 

# Version History
#### Be careful, the technical part starts here.

## 1.5

* It is now possible to choose the number of Stamina Potions to be used. Choose between "Do Not Use", "Use 3", "Use 6", "Use 10", "Use 15" and "Use MAX" modes.

* Added slow mode and fast mode.
  
  * Slow Mode: For unstable and slow connections. Checks and waits take longer to match the communication time between game and server.
  
  * Fast mode: for fast and stable connections. Checks and waits happen faster. Excellent for farming without wasting a lot of time.
  
  * Note that Expeditions checks and waits are not affected by these settings.

* Now the macro auto-stops. Auto-stop works in two situations:
  
  * Idle: When the macro is running, it checks if battles are taking place. If the macro doesn't detect a battle, its counter starts increasing from 1 to 15. When the 15th check doesn't detect a battle, the macro stops automatically. If a battle is detected or expedition starts, the counter resets.
  
  * Connection Error: When the macro is running and it detects a connection failure, it starts counting the number of reconnection attempts ranging from 1 to 10. When the 10th attempt occurs, the macro will stop. If a battle is detected, the counter resets.
  
  * Note that the verification speed depends on the chosen speed mode.

* To avoid accidents, pause the macro when navigating somewhere in the game other than battles or expeditions. (Remember that the macro does not automatically start a battle and just looks for the "rematch" button)

* Last but not least, as soon as you start the macro, after the initial setup, a small summary will be displayed on the screen that contains:
  
  * Speed Mode,
  
  * Number of Stamina Potions used,
  
  * Number of Rematches (does not take into account wins or losses ),
  
  * Battle Detect Failure Counter,
  
  * Reconnection Attempts Counter.

## 1.4

* Added Expeditions support;

* Added fallback confirmation checkers. They are necessary because under different network conditions, some actions may be delayed and some checks do not occur at the right time. These checkers serve to cancel or confirm game actions in order to provide correct functioning;

* Improved detection areas. Image checks now cover a larger area, and take place in predefined segments, making the sizes standard and compatible with various screen aspect ratios.

## 1.3 and 1.3.1 

* Improved detection of elements in different screen formats. (Tested on devices with 9:16, 9:18 and 9:19 aspect ratios and 720p and 1080p resolutions);

* New approach to spot battles;

* Stamina recovery tested and stable;

* Other code improvements.

## 1.2

* Initial implementation of stamina recovery;

* Macro now uses functions to organize and automate parts of the code.

## 1.0

* Simple image detection. Cycle rematch / battle detect / rank up confirmation.