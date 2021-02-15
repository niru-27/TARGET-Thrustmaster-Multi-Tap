# TARGET-Thrustmaster-Multi-Tap
Add double tap, triple tap, etc detection to your TMC scripts.

## Detection examples :
* **single tap**
* **single tap + hold** aka Long Press (just like Tempo)
* **double tap**
* **double tap + hold**
* ...
* **n number of taps** with/without hold at end


## How to :
Each button that you want to assign outputs to needs the following:
* **define ButtonName n** - the index in the array where the corresponding button's tap counts are stored
* **MapKey**
* **MapKeyR**
* **MultiTap_ButtonName()** - Assign individual commands to be performed upon tap/long press/double tap, etc
