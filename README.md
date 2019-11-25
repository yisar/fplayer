# cplayer
flutter player for clicli.tv

```dart
CPlayerController _controller = CPlayerController(
    url: 'https://www.clicli.me/001.mp4',
    flags: CPlayerFlags(
        autoPlay: true,
        mute: true,
    ),
);

CPlayer(
    controller: _controller,
    themeColor: Colors.purple,
    onReady () {
        _controller.addListener(listener);
    },
),
```
