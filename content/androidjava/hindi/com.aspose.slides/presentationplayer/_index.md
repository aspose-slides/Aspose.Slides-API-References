---
title: PresentationPlayer
second_title: Java API संदर्भ के माध्यम से Aspose.Slides for Android
description: एनीमेशन प्लेयर का प्रतिनिधित्व करता है जो संबंधित है।
type: docs
url: /hi/com.aspose.slides/presentationplayer/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
com.aspose.ms.System.IDisposable
```
public class PresentationPlayer implements System.IDisposable
```

[Presentation](../../com.aspose.slides/presentation) से जुड़े एनीमेशन प्लेयर का प्रतिनिधित्व करता है।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          // 33 FPS के साथ एनीमेशन चलाएँ
>          PresentationPlayer player33 = new PresentationPlayer(animationsGenerator, 33);
>          try {
>              player33.setFrameTick(new PresentationPlayer.FrameTick() {
>                  public void invoke(PresentationPlayer sender, FrameTickEventArgs args) {
>                      FileOutputStream fos = null;
>                      try {
>                          fos = new FileOutputStream("33fps/frame_" + sender.getFrameIndex() + ".png");
>                          args.getFrame().compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>                      } catch (IOException e) {
>                          throw new RuntimeException(e);
>                      } finally {
>                          if (fos != null) {
>                              try {
>                                  fos.close();
>                              } catch (IOException e) {
>                                  e.printStackTrace();
>                              }
>                          }
>                      }
>                  }
>              });
>              animationsGenerator.run(pres.getSlides());
>          } finally {
>              if (player33 != null) player33.dispose();
>          }
>          // 45 FPS के साथ एनीमेशन चलाएँ
>          PresentationPlayer player45 = new PresentationPlayer(animationsGenerator, 45);
>          try {
>              player45.setFrameTick(new PresentationPlayer.FrameTick() {
>                  public void invoke(PresentationPlayer sender, FrameTickEventArgs args) {
>                      FileOutputStream fos = null;
>                      try {
>                          fos = new FileOutputStream("45fps/frame_" + sender.getFrameIndex() + ".png");
>                          args.getFrame().compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>                      } catch (IOException e) {
>                          throw new RuntimeException(e);
>                      } finally {
>                          if (fos != null) {
>                              try {
>                                  fos.close();
>                              } catch (IOException e) {
>                                  e.printStackTrace();
>                              }
>                          }
>                      }
>                  }
>              });
>              animationsGenerator.run(pres.getSlides());
>          } finally {
>              if (player45 != null) player45.dispose();
>          }
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Constructors

| Constructor | Description |
| --- | --- |
| [PresentationPlayer(PresentationAnimationsGenerator generator, double fps)](#PresentationPlayer-com.aspose.slides.PresentationAnimationsGenerator-double-) | [PresentationPlayer](../../com.aspose.slides/presentationplayer) का नया उदाहरण बनाता है। |
## Methods

| Method | Description |
| --- | --- |
| [dispose()](#dispose--) | [PresentationPlayer](../../com.aspose.slides/presentationplayer) का उदाहरण नष्ट करता है। |
| [getFrameIndex()](#getFrameIndex--) | फ़्रेम सूचकांक प्राप्त करता है। |
| [setFrameTick(PresentationPlayer.FrameTick event)](#setFrameTick-com.aspose.slides.PresentationPlayer.FrameTick-) | नया फ़्रेम टिक इवेंट सेट करता है। |
### PresentationPlayer(PresentationAnimationsGenerator generator, double fps) {#PresentationPlayer-com.aspose.slides.PresentationAnimationsGenerator-double-}
```
public PresentationPlayer(PresentationAnimationsGenerator generator, double fps)
```


नया उदाहरण बनाता है [PresentationPlayer](../../com.aspose.slides/presentationplayer) का।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) | प्रेजेंटेशन एनीमेशन जेनरेटर |
| fps | double | फ़्रेम प्रति सेकंड (FPS) |

### dispose() {#dispose--}
```
public final void dispose()
```


[PresentationPlayer](../../com.aspose.slides/presentationplayer) का उदाहरण नष्ट करता है।

### getFrameIndex() {#getFrameIndex--}
```
public final int getFrameIndex()
```


फ़्रेम सूचकांक प्राप्त करता है।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          PresentationPlayer player = new PresentationPlayer(animationsGenerator, 33);
>          try {
>              player.setFrameTick(new PresentationPlayer.FrameTick() {
>                  public void invoke(PresentationPlayer sender, FrameTickEventArgs args) {
>                      FileOutputStream fos = null;
>                      try {
>                          fos = new FileOutputStream("frame_" + sender.getFrameIndex() + ".png");
>                          args.getFrame().compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>                      } catch (IOException e) {
>                          throw new RuntimeException(e);
>                      } finally {
>                          if (fos != null) {
>                              try {
>                                  fos.close();
>                              } catch (IOException e) {
>                                  e.printStackTrace();
>                              }
>                          }
>                      }
>                  }
>              });
>              animationsGenerator.run(pres.getSlides());
>          } finally {
>              if (player != null) player.dispose();
>          }
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
int
### setFrameTick(PresentationPlayer.FrameTick event) {#setFrameTick-com.aspose.slides.PresentationPlayer.FrameTick-}
```
public void setFrameTick(PresentationPlayer.FrameTick event)
```


नया फ़्रेम टिक इवेंट सेट करता है।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PresentationAnimationsGenerator animationsGenerator = new PresentationAnimationsGenerator(pres);
>      try {
>          PresentationPlayer player = new PresentationPlayer(animationsGenerator, 33);
>          try {
>              player.setFrameTick(new PresentationPlayer.FrameTick() {
>                  public void invoke(PresentationPlayer sender, FrameTickEventArgs args) {
>                      FileOutputStream fos = null;
>                      try {
>                          fos = new FileOutputStream("frame_" + sender.getFrameIndex() + ".png");
>                          args.getFrame().compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>                      } catch (IOException e) {
>                          throw new RuntimeException(e);
>                      } finally {
>                          if (fos != null) {
>                              try {
>                                  fos.close();
>                              } catch (IOException e) {
>                                  e.printStackTrace();
>                              }
>                          }
>                      }
>                  }
>              });
>              animationsGenerator.run(pres.getSlides());
>          } finally {
>              if (player != null) player.dispose();
>          }
>      } finally {
>          if (animationsGenerator != null) animationsGenerator.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

जब [PresentationAnimationsGenerator](../../com.aspose.slides/presentationanimationsgenerator) द्वारा निर्मित एनीमेशन का प्रत्येक फ़्रेम प्लेयर द्वारा जेनरेट किया जाता है, तब यह घटित होता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| event | [FrameTick](../../com.aspose.slides/frametick) | फ़्रेम टिक इवेंट। |