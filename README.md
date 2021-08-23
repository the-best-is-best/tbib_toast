# Toast

A Flutter Toast plugin.


```dart
Toast.show("Toast plugin app", context, duration: Toast.LENGTH_SHORT, gravity:  Toast.BOTTOM);
```

property | description
--------|------------
msg | String (Not Null)(required)
context | BuildContext (Not Null)(required)
duration| Toast.LENGTH_SHORT or Toast.LENGTH_LONG (optional)
gravity | Toast.TOP (or) Toast.CENTER (or) Toast.BOTTOM
textStyle | TextStyle (default fontSize:15, color: Colors.white)
backgroundColor | Color (default Color(0xAA000000))
backgroundRadius | double ï¼ˆdefault 16)
border| Border (optional)


![toast](https://github.com/huclengyue/FlutterToast/blob/master/screenshot/141107.png)
![toast](https://github.com/huclengyue/FlutterToast/blob/master/screenshot/141134.png)


## License

    MIT License

