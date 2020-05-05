## ![160x160](.\Doc\160x160.png)

[OneString]( https://assetstore.unity.com/packages/slug/168465 
) is a 0 GC ToString solution. Traditional numbers or bool variables converted to strings will have GC. Mainly because strings are immutable. Each time the string is modified, a new string is renewed. If we
need to temporarily print a certain value, using the system's ToString function will inevitably generate a new string, which we don't want to see. Therefore, a string that can be used temporarily is needed, and it can be recycled after use. OneString is such a solution. It should be noted that such as the UGUI Text component is used for display, do not use this method. Because the value of text will be modified.

![420x280](.\Doc\420x280.png)



## Features

- 0 GC：To String takes 0 GC. 
- Support int、long、float、double、bool, etc. 
- Support the setting of the number of decimal places, and the default is to keep two decimal places.
- Easy to use: Just use ToOneString() function, it will return a string.
- Support expansion and modification.
- Contains complete code and demo scenarios. 

## Installation

Player Settings: Tick Allow ‘unsafe’ Code. 

![PlayerSettings](.\Doc\PlayerSettings.png)                                      

Just use ToOneString() function, it will return a string.

## Documents

[PDF](.\Doc\README.pdf)

## Release Note

### 1.0.1

Init release 

## Contact

For more detail you can go to the web:   https://assetstore.unity.com/packages/slug/168465 

Email: [936496193@qq.com](mailto:936496193@qq.com)