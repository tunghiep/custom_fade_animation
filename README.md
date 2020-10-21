## ⛏️ Getting started

Add **Custom Fade Animation** to your project by following the instructions on the 
**[install page](https://pub.dev/packages/custom_fade_animation/install)** and start using it:
```dart
import 'package:custom_fade_animation/custom_fade_animation.dart';
```
### 📈 Usage

Provide an FadeAnimation class which wrap around any widget and add fade animation to its child.

```dart
FadeAnimation(1.8, Container(
                        padding: EdgeInsets.all(5),
                        decoration: BoxDecoration(
                            color: Colors.white,
                            borderRadius: BorderRadius.circular(10),
                            boxShadow: [
                              BoxShadow(
                                  color: Color.fromRGBO(143, 148, 251, .2),
                                  blurRadius: 20.0,
                                  offset: Offset(0, 10)
                              )
                            ]
                        ),
```
