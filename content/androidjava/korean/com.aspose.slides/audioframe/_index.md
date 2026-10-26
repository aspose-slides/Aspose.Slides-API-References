---
title: AudioFrame
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 슬라이드에 있는 오디오 클립을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/audioframe/
---
**상속:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IAudioFrame](../../com.aspose.slides/iaudioframe)  
```
public class AudioFrame extends PictureFrame implements IAudioFrame
```

슬라이드의 오디오 클립을 나타냅니다.

--------------------

> ```
> The following examples shows how to change Audio Play Options.
>   
>  Presentation pres = new Presentation("AudioFrameEmbed_out.pptx");
>  try {
>      // AudioFrame 모양을 가져옵니다
>      AudioFrame audioFrame = (AudioFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // 재생 모드를 클릭 시 재생으로 설정합니다
>      audioFrame.setPlayMode(AudioPlayModePreset.OnClick);
>      // 볼륨을 낮음으로 설정합니다
>      audioFrame.setVolume(AudioVolumeMode.Low);
>      // 오디오를 슬라이드 전체에서 재생하도록 설정합니다
>      audioFrame.setPlayAcrossSlides(true);
>      // 오디오 루프를 비활성화합니다
>      audioFrame.setPlayLoopMode(false);
>      // 슬라이드 쇼 중 AudioFrame을 숨깁니다
>      audioFrame.setHideAtShowing(true);
>      // 재생 후 오디오를 시작으로 되감습니다
>      audioFrame.setRewindAudio(true);
>      // PowerPoint 파일을 디스크에 저장합니다
>      pres.save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 메서드

| Method | Description |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | 시작 트랙 인덱스를 반환하거나 설정합니다. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | 시작 트랙 인덱스를 반환하거나 설정합니다. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | 시작 트랙 시간을 반환하거나 설정합니다. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | 시작 트랙 시간을 반환하거나 설정합니다. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | 마지막 트랙 인덱스를 반환하거나 설정합니다 읽기/쓰기  int . |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | 마지막 트랙 인덱스를 반환하거나 설정합니다 읽기/쓰기  int . |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | 마지막 트랙 시간을 반환하거나 설정합니다. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | 마지막 트랙 시간을 반환하거나 설정합니다. |
| [getVolume()](#getVolume--) | 오디오 볼륨을 반환하거나 설정합니다. |
| [setVolume(int value)](#setVolume-int-) | 오디오 볼륨을 반환하거나 설정합니다. |
| [getPlayMode()](#getPlayMode--) | 오디오 재생 모드를 반환하거나 설정합니다. |
| [setPlayMode(int value)](#setPlayMode-int-) | 오디오 재생 모드를 반환하거나 설정합니다. |
| [getHideAtShowing()](#getHideAtShowing--) | AudioFrame이 숨겨져 있는지 여부를 판단합니다. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | AudioFrame이 숨겨져 있는지 여부를 판단합니다. |
| [getPlayLoopMode()](#getPlayLoopMode--) | 오디오가 반복되는지 여부를 판단합니다. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | 오디오가 반복되는지 여부를 판단합니다. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | 오디오가 슬라이드 전체에서 재생되는지 여부를 판단합니다. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | 오디오가 슬라이드 전체에서 재생되는지 여부를 판단합니다. |
| [getRewindAudio()](#getRewindAudio--) | 오디오가 재생 후 자동으로 시작으로 되감기되는지 여부를 판단합니다. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | 오디오가 재생 후 자동으로 시작으로 되감기되는지 여부를 판단합니다. |
| [getEmbedded()](#getEmbedded--) | 사운드가 프레젠테이션에 삽입되었는지 여부를 판단합니다. |
| [getLinkPathLong()](#getLinkPathLong--) | AudioFrame에 연결된 오디오 파일 이름을 반환하거나 설정합니다. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | AudioFrame에 연결된 오디오 파일 이름을 반환하거나 설정합니다. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | 삽입된 오디오 객체를 반환하거나 설정합니다. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | 삽입된 오디오 객체를 반환하거나 설정합니다. |
| [getFadeInDuration()](#getFadeInDuration--) | 미디어의 초기 페이드 인 시간 지속 시간을 밀리초 단위로 지정합니다. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | 미디어의 초기 페이드 인 시간 지속 시간을 밀리초 단위로 지정합니다. |
| [getFadeOutDuration()](#getFadeOutDuration--) | 미디어의 종료 페이드 아웃 시간 지속 시간을 밀리초 단위로 지정합니다. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | 미디어의 종료 페이드 아웃 시간 지속 시간을 밀리초 단위로 지정합니다. |
| [getVolumeValue()](#getVolumeValue--) | 오디오 볼륨을 퍼센트 단위로 반환하거나 설정합니다. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | 오디오 볼륨을 퍼센트 단위로 반환하거나 설정합니다. |
| [getTrimFromStart()](#getTrimFromStart--) | 재생 중 미디어 시작 부분에서 제거될 시간 지속 시간을 밀리초 단위로 지정합니다. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | 재생 중 미디어 시작 부분에서 제거될 시간 지속 시간을 밀리초 단위로 지정합니다. |
| [getTrimFromEnd()](#getTrimFromEnd--) | 재생 중 미디어 끝 부분에서 제거될 시간 지속 시간을 밀리초 단위로 지정합니다. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | 재생 중 미디어 끝 부분에서 제거될 시간 지속 시간을 밀리초 단위로 지정합니다. |
| [getCaptionTracks()](#getCaptionTracks--) | 오디오 프레임과 연결된 폐쇄 캡션 컬렉션을 가져옵니다. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public final int getAudioCdStartTrack()
```

시작 트랙 인덱스를 반환하거나 설정합니다. 읽기/쓰기  int .

**반환값:**
int

### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public final void setAudioCdStartTrack(int value)
```

시작 트랙 인덱스를 반환하거나 설정합니다. 읽기/쓰기  int .

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public final int getAudioCdStartTrackTime()
```

시작 트랙 시간을 반환하거나 설정합니다. 읽기/쓰기  int .

**반환값:**
int

### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public final void setAudioCdStartTrack(int value)
```

시작 트랙 시간을 반환하거나 설정합니다. 읽기/쓰기  int .

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public final int getAudioCdEndTrack()
```

마지막 트랙 인덱스를 반환하거나 설정합니다 읽기/쓰기  int .

**반환값:**
int

### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public final void setAudioCdEndTrack(int value)
```

마지막 트랙 인덱스를 반환하거나 설정합니다 읽기/쓰기  int .

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public final int getAudioCdEndTrackTime()
```

마지막 트랙 시간을 반환하거나 설정합니다. 읽기/쓰기  int .

**반환값:**
int

### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public final void setAudioCdEndTrackTime(int value)
```

마지막 트랙 시간을 반환하거나 설정합니다. 읽기/쓰기  int .

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

오디오 볼륨을 반환하거나 설정합니다. 읽기/쓰기 [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**반환값:**
int

### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

오디오 볼륨을 반환하거나 설정합니다. 읽기/쓰기 [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

오디오 재생 모드를 반환하거나 설정합니다. 읽기/쓰기 [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**반환값:**
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

오디오 재생 모드를 반환하거나 설정합니다. 읽기/쓰기 [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

AudioFrame이 숨겨져 있는지 여부를 판단합니다. 읽기/쓰기  boolean .

**반환값:**
boolean

### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

AudioFrame이 숨겨져 있는지 여부를 판단합니다. 읽기/쓰기  boolean .

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

오디오가 반복되는지 여부를 판단합니다. 읽기/쓰기  boolean .

**반환값:**
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

오디오가 반복되는지 여부를 판단합니다. 읽기/쓰기  boolean .

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public final boolean getPlayAcrossSlides()
```

오디오가 슬라이드 전체에서 재생되는지 여부를 판단합니다. 읽기/쓰기  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // 오디오 프레임 추가
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // 오디오를 슬라이드 전체에서 재생하도록 설정
>       audioFrame.setPlayAcrossSlides(true);
>       // 재생 후 오디오를 자동으로 시작으로 되감도록 설정
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**반환값:**
boolean

### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public final void setPlayAcrossSlides(boolean value)
```

오디오가 슬라이드 전체에서 재생되는지 여부를 판단합니다. 읽기/쓰기  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // 오디오 프레임 추가
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // 오디오를 슬라이드 전체에서 재생하도록 설정
>       audioFrame.setPlayAcrossSlides(true);
>       // 재생 후 오디오를 자동으로 시작으로 되감도록 설정
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public final boolean getRewindAudio()
```

오디오가 재생 후 자동으로 시작으로 되감기되는지 여부를 판단합니다. 읽기/쓰기  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // 오디오 프레임 추가
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // 오디오를 슬라이드 전체에서 재생하도록 설정
>       audioFrame.setPlayAcrossSlides(true);
>       // 재생 후 오디오를 자동으로 시작으로 되감도록 설정
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**반환값:**
boolean

### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public final void setRewindAudio(boolean value)
```

오디오가 재생 후 자동으로 시작으로 되감기되는지 여부를 판단합니다. 읽기/쓰기  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // 오디오 프레임 추가
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // 오디오를 슬라이드 전체에서 재생하도록 설정
>       audioFrame.setPlayAcrossSlides(true);
>       // 재생 후 오디오를 자동으로 시작으로 되감도록 설정
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public final boolean getEmbedded()
```

사운드가 프레젠테이션에 삽입되었는지 여부를 판단합니다. 읽기 전용  boolean .

**반환값:**
boolean

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

AudioFrame에 연결된 오디오 파일 이름을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환값:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

AudioFrame에 연결된 오디오 파일 이름을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public final IAudio getEmbeddedAudio()
```

삽입된 오디오 객체를 반환하거나 설정합니다. 읽기/쓰기 [IAudio](../../com.aspose.slides/iaudio).

**반환값:**
[IAudio](../../com.aspose.slides/iaudio)

### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public final void setEmbeddedAudio(IAudio value)
```

삽입된 오디오 객체를 반환하거나 설정합니다. 읽기/쓰기 [IAudio](../../com.aspose.slides/iaudio).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public final float getFadeInDuration()
```

미디어의 초기 페이드 인 시간 지속 시간을 밀리초 단위로 지정합니다. 읽기/쓰기 float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 시작 페이드 지속 시간을 200ms로 설정합니다
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환값:**
float

### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public final void setFadeInDuration(float value)
```

미디어의 초기 페이드 인 시간 지속 시간을 밀리초 단위로 지정합니다. 읽기/쓰기 float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 시작 페이드 지속 시간을 200ms로 설정합니다
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public final float getFadeOutDuration()
```

미디어의 종료 페이드 아웃 시간 지속 시간을 밀리초 단위로 지정합니다. 읽기/쓰기 float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 종료 페이드 지속 시간을 500ms로 설정합니다
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환값:**
float

### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public final void setFadeOutDuration(float value)
```

미디어의 종료 페이드 아웃 시간 지속 시간을 밀리초 단위로 지정합니다. 읽기/쓰기 float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 종료 페이드 지속 시간을 500ms로 설정합니다
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public final float getVolumeValue()
```

오디오 볼륨을 퍼센트 단위로 반환하거나 설정합니다. 읽기/쓰기 float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 오디오 볼륨을 85%로 설정합니다
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환값:**
float

### setVolumeValue(float value) {#setVolumeValue-float-}
```
public final void setVolumeValue(float value)
```

오디오 볼륨을 퍼센트 단위로 반환하거나 설정합니다. 읽기/쓰기 float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 오디오 볼륨을 85%로 설정합니다
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

재생 중 미디어 시작 부분에서 제거될 시간 지속 시간을 밀리초 단위로 지정합니다. 읽기/쓰기 float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 시작 트리밍 시간을 1.5초로 설정합니다
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환값:**
float

### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```

재생 중 미디어 시작 부분에서 제거될 시간 지속 시간을 밀리초 단위로 지정합니다. 읽기/쓰기 float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 시작 트리밍 시간을 1.5초로 설정합니다
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public final float getTrimFromEnd()
```

재생 중 미디어 끝 부분에서 제거될 시간 지속 시간을 밀리초 단위로 지정합니다. 읽기/쓰기 float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 종료 트리밍 시간을 2초로 설정합니다
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환값:**
float

### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

재생 중 미디어 끝 부분에서 제거될 시간 지속 시간을 밀리초 단위로 지정합니다. 읽기/쓰기 float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 종료 트리밍 시간을 2초로 설정합니다
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

오디오 프레임과 연결된 폐쇄 캡션 컬렉션을 가져옵니다. 이 속성은 읽기 전용이며 모든 캡션 트랙을 포함하는 [ICaptionsCollection](../../com.aspose.slides/icaptionscollection)를 반환합니다.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("audio with captions.pptx");
>  try {
>      for (IShape shape : pres.getSlides().get_Item(0).getShapes())
>      {
>          if (shape instanceof IAudioFrame)
>          {
>              IAudioFrame audioFrame = (IAudioFrame) shape;
>              // 캡션 트랙의 바이너리 데이터를 .vtt 파일로 저장합니다
>              for (ICaptions captionTrack : audioFrame.getCaptionTracks()) {
>                  FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>                  fos.write(captionTrack.getBinaryData());
>                  fos.close();
>              }
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환값:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)