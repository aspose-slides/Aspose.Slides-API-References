---
title: Hyperlink
second_title: Aspose.Slides for Android via Java API 레퍼런스
description: 하이퍼링크를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/hyperlink/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IHyperlink](../../com.aspose.slides/ihyperlink), com.aspose.slides.IDOMObject
```
public final class Hyperlink extends PVIObject implements IHyperlink, IDOMObject
```

Hyperlink을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | Hyperlink의 인스턴스를 생성합니다. |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | 특정 슬라이드를 가리키는 Hyperlink의 인스턴스를 생성합니다. |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | 다른 Hyperlink을 소스로 사용하여 보조 속성을 재정의한 Hyperlink 인스턴스를 생성합니다. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | 특수 "do nothing" Hyperlink을 반환합니다. |
| [getMedia()](#getMedia--) | 특수 "play mediafile" Hyperlink을 반환합니다. |
| [getNextSlide()](#getNextSlide--) | 다음 슬라이드로 이동하는 Hyperlink을 반환합니다. |
| [getPreviousSlide()](#getPreviousSlide--) | 이전 슬라이드로 이동하는 Hyperlink을 반환합니다. |
| [getFirstSlide()](#getFirstSlide--) | 프레젠테이션의 첫 슬라이드로 이동하는 Hyperlink을 반환합니다. |
| [getLastSlide()](#getLastSlide--) | 프레젠테이션의 마지막 슬라이드로 이동하는 Hyperlink을 반환합니다. |
| [getLastVievedSlide()](#getLastVievedSlide--) | 마지막으로 본 슬라이드로 이동하는 Hyperlink을 반환합니다. |
| [getEndShow()](#getEndShow--) | 쇼를 종료하는 Hyperlink을 반환합니다. |
| [getActionType()](#getActionType--) | Hyperlink 동작의 유형을 반환합니다. |
| [getExternalUrl()](#getExternalUrl--) | 외부 URL을 지정합니다. |
| [getTargetSlide()](#getTargetSlide--) | Hyperlink이 특정 슬라이드를 대상으로 하는 경우 해당 슬라이드를 반환합니다. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | 부분의 실제 내용과 무관하게 이 부분에 설정된 Hyperlink을 나타냅니다. |
| [getTargetFrame()](#getTargetFrame--) | 부모 Hyperlink의 대상이 존재할 경우, 부모 HTML 프레임셋 내의 프레임을 반환합니다. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | 부모 Hyperlink의 대상이 존재할 경우, 부모 HTML 프레임셋 내의 프레임을 반환합니다. |
| [getTooltip()](#getTooltip--) | 부모 Hyperlink과 연결된 사용자 인터페이스에 표시될 수 있는 문자열을 반환합니다. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | 부모 Hyperlink과 연결된 사용자 인터페이스에 표시될 수 있는 문자열을 반환합니다. |
| [getHistory()](#getHistory--) | 부모 Hyperlink의 대상이 호출될 때 조회된 Hyperlink 목록에 추가될지 여부를 결정합니다. |
| [setHistory(boolean value)](#setHistory-boolean-) | 부모 Hyperlink의 대상이 호출될 때 조회된 Hyperlink 목록에 추가될지 여부를 결정합니다. |
| [getHighlightClick()](#getHighlightClick--) | 클릭 시 Hyperlink을 강조 표시할지 여부를 결정합니다. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | 클릭 시 Hyperlink을 강조 표시할지 여부를 결정합니다. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | 클릭 시 사운드를 중지할지 여부를 결정합니다. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | 클릭 시 사운드를 중지할지 여부를 결정합니다. |
| [getSound()](#getSound--) | Hyperlink의 재생 사운드를 나타냅니다. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Hyperlink의 재생 사운드를 나타냅니다. |
| [getColorSource()](#getColorSource--) | Hyperlink 색상의 소스(스타일 또는 부분 서식)를 나타냅니다. |
| [setColorSource(int value)](#setColorSource-int-) | Hyperlink 색상의 소스(스타일 또는 부분 서식)를 나타냅니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 두 Hyperlink 인스턴스가 같은지 여부를 판단합니다. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | 두 Hyperlink 인스턴스가 같은지 여부를 판단합니다. |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | 두 Hyperlink이 같은지 테스트합니다. |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | 두 Hyperlink이 다른지 테스트합니다. |
| [hashCode()](#hashCode--) | 특정 유형에 대한 해시 함수를 제공하며, 해시 테이블과 같은 해싱 알고리즘 및 데이터 구조에 사용할 수 있습니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

Hyperlink의 인스턴스를 생성합니다.

**Parameters:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| url | java.lang.String | Hyperlink URL. |

### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

특정 슬라이드를 가리키는 Hyperlink의 인스턴스를 생성합니다. Note: created hyperlink should be assigned to some object from the same presentation, otherwise link will be saved as NoAction.

**Parameters:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | 대상 슬라이드. |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

다른 Hyperlink을 소스로 사용하여 보조 속성을 재정의한 Hyperlink 인스턴스를 생성합니다.

**Parameters:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | 소스 Hyperlink |
| targetFrame | java.lang.String | 대상 프레임 |
| tooltip | java.lang.String | 툴팁 텍스트 |
| history | boolean | 부모 Hyperlink의 대상이 호출될 때 조회된 Hyperlink 목록에 추가될지 여부를 결정합니다. |
| stopSoundsOnClick | boolean | 클릭 시 사운드를 중지할지 여부를 결정합니다. |
| highlightClick | boolean | 클릭 시 Hyperlink을 강조 표시할지 여부를 결정합니다. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

버전. 읽기 전용 long.

**Returns:**
long

### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

특수 "do nothing" Hyperlink을 반환합니다. 읽기 전용 [Hyperlink](../../com.aspose.slides/hyperlink).

**Returns:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

특수 "play mediafile" Hyperlink을 반환합니다. Used in AudioFrame and VideoFrame. 읽기 전용 [Hyperlink](../../com.aspose.slides/hyperlink).

**Returns:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

다음 슬라이드로 이동하는 Hyperlink을 반환합니다. 읽기 전용 [Hyperlink](../../com.aspose.slides/hyperlink).

**Returns:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

이전 슬라이드로 이동하는 Hyperlink을 반환합니다. 읽기 전용 [Hyperlink](../../com.aspose.slides/hyperlink).

**Returns:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

프레젠테이션의 첫 슬라이드로 이동하는 Hyperlink을 반환합니다. 읽기 전용 [Hyperlink](../../com.aspose.slides/hyperlink).

**Returns:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

프레젠테이션의 마지막 슬라이드로 이동하는 Hyperlink을 반환합니다. 읽기 전용 [Hyperlink](../../com.aspose.slides/hyperlink).

**Returns:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

마지막으로 본 슬라이드로 이동하는 Hyperlink을 반환합니다. 읽기 전용 [Hyperlink](../../com.aspose.slides/hyperlink).

**Returns:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

쇼를 종료하는 Hyperlink을 반환합니다. 읽기 전용 [Hyperlink](../../com.aspose.slides/hyperlink).

**Returns:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getActionType() {#getActionType--}
```
public final int getActionType()
```

Hyperlink 동작의 유형을 반환합니다. 읽기 전용 [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Returns:**
int

### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

외부 URL을 지정합니다. 읽기 전용 String.

**Returns:**
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

Hyperlink이 특정 슬라이드를 대상으로 하는 경우 해당 슬라이드를 반환합니다. 읽기 전용 [ISlide](../../com.aspose.slides/islide).

**Returns:**
[ISlide](../../com.aspose.slides/islide)

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

부분의 실제 내용과 무관하게 이 부분에 설정된 Hyperlink을 나타냅니다.

**Returns:**
java.lang.String

--------------------

PowerPoint behaves specifically for links and their corresponding text in a portion. It allows to create text for the hyperlink in the form of a valid URL, different from the real address of the link. In this case, when you view the link in the edit window, it will be changed to match the text portion. This property represents the original value of the hyperlink.

**Returns:**
java.lang.String

### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

부모 Hyperlink의 대상이 존재할 경우, 부모 HTML 프레임셋 내의 프레임을 반환합니다. 읽기/쓰기 String.

**Returns:**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

부모 Hyperlink의 대상이 존재할 경우, 부모 HTML 프레임셋 내의 프레임을 반환합니다. 읽기/쓰기 String.

**Parameters:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

부모 Hyperlink과 연결된 사용자 인터페이스에 표시될 수 있는 문자열을 반환합니다. 읽기/쓰기 String.

**Returns:**
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

부모 Hyperlink과 연결된 사용자 인터페이스에 표시될 수 있는 문자열을 반환합니다. 읽기/쓰기 String.

**Parameters:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

부모 Hyperlink의 대상이 호출될 때 조회된 Hyperlink 목록에 추가될지 여부를 결정합니다. 읽기/쓰기 boolean.

**Returns:**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

부모 Hyperlink의 대상이 호출될 때 조회된 Hyperlink 목록에 추가될지 여부를 결정합니다. 읽기/쓰기 boolean.

**Parameters:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

클릭 시 Hyperlink을 강조 표시할지 여부를 결정합니다. 읽기/쓰기 boolean.

**Returns:**
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

클릭 시 Hyperlink을 강조 표시할지 여부를 결정합니다. 읽기/쓰기 boolean.

**Parameters:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

클릭 시 사운드를 중지할지 여부를 결정합니다. 읽기/쓰기 boolean.

**Returns:**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

클릭 시 사운드를 중지할지 여부를 결정합니다. 읽기/쓰기 boolean.

**Parameters:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Hyperlink의 재생 사운드를 나타냅니다. 읽기/쓰기 [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // 첫 번째 도형의 하이퍼링크를 가져옵니다
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // 하이퍼링크 사운드를 바이트 배열로 추출합니다
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Returns:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Hyperlink의 재생 사운드를 나타냅니다. 읽기/쓰기 [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // 첫 번째 도형의 하이퍼링크를 가져옵니다
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // 하이퍼링크 사운드를 바이트 배열로 추출합니다
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getColorSource() {#getColorSource--}
```
public final int getColorSource()
```

Hyperlink 색상의 소스(스타일 또는 부분 서식)를 나타냅니다. 읽기/쓰기 [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Returns:**
int

### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

Hyperlink 색상의 소스(스타일 또는 부분 서식)를 나타냅니다. 읽기/쓰기 [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Parameters:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

두 Hyperlink 인스턴스가 같은지 여부를 판단합니다.

**Parameters:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 현재 Hyperlink과 비교할 Hyperlink. |

**Returns:**
boolean - **true** if the specified Hyperlink is equal to the current Hyperlink; otherwise, **false**.

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

두 Hyperlink 인스턴스가 같은지 여부를 판단합니다.

**Parameters:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | 현재 Hyperlink과 비교할 Hyperlink. |

**Returns:**
boolean - **true** if the specified Hyperlink is equal to the current Hyperlink; otherwise, **false**.

### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

두 Hyperlink이 같은지 테스트합니다.

**Parameters:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | 첫 번째 테스트 대상 Hyperlink. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | 두 번째 테스트 대상 Hyperlink. |

**Returns:**
boolean - **true** if hyperlinks are equal.

### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

두 Hyperlink이 다른지 테스트합니다.

**Parameters:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | 첫 번째 테스트 대상 Hyperlink. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | 두 번째 테스트 대상 Hyperlink. |

**Returns:**
boolean - **false** if hyperlinks are equal.

### hashCode() {#hashCode--}
```
public int hashCode()
```

특정 유형에 대한 해시 함수를 제공하며, 해시 테이블과 같은 해싱 알고리즘 및 데이터 구조에 사용할 수 있습니다.

**Returns:**
int - URL의 해시 코드.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject