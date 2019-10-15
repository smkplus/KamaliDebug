# KamaliDebug
Easy way to Debug Colorful Texts in Unity Console

![image](https://user-images.githubusercontent.com/16706911/66837274-97480a80-ef6f-11e9-82c3-c91790c21de1.png)

```
    private void Start()
    {
    DebugX.Log(@"I:orange:b; love:red:b; Unity:yellow:b;
    ColorfullllllllllllllllText:rainbow:b;");
    
    DebugX.Log("sniper:orange:b; bug:green:b;");

    }
```

<H3> Syntax </H3>

```(Text or Emoji):Color:TextStyle;```

_______


<H3> Font Color </H3>

```DebugX.Log("Hello world:green;");```

_______


![image](https://user-images.githubusercontent.com/16706911/66838611-d2e3d400-ef71-11e9-8721-c71773f4cd79.png)

<H3> Font Style </H3>

```DebugX.Log("Hello world:b;");```

_______
    
![image](https://user-images.githubusercontent.com/16706911/66838211-286bb100-ef71-11e9-8b01-1013f6be07ab.png)


<H3> Emoji </H3>

```DebugX.Log("love:red:b; love:red:b; love:red:b;");```


![image](https://user-images.githubusercontent.com/16706911/66839173-dd529d80-ef72-11e9-9010-eac6aaf06411.png)


_______

<H3> Complex </H3>

```DebugX.Log("Hello:yellow:b; world:red:b;");```

![image](https://user-images.githubusercontent.com/16706911/66838419-7da7c280-ef71-11e9-83c6-d0dda9d5d75f.png)


___________

ToDo:

1.Add more fontstyles , colors and emojis

2.Make ScriptableObject for Colors
