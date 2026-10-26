---
title: Hyperlink
second_title: Aspose.Slides for Java API 레퍼런스
description: 하이퍼링크를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/hyperlink/
---
**상속:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**구현된 모든 인터페이스:**
[com.aspose.slides.IHyperlink](../../com.aspose.slides/ihyperlink), com.aspose.slides.IDOMObject
```
public final class Hyperlink extends PVIObject implements IHyperlink, IDOMObject
```

하이퍼링크를 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | 하이퍼링크의 인스턴스를 생성합니다. |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | 특정 슬라이드를 가리키는 하이퍼링크의 인스턴스를 생성합니다. |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | 다른 하이퍼링크를 소스로 사용하고 보조 속성을 재정의하여 하이퍼링크의 인스턴스를 생성합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | 특수한 "do nothing" 하이퍼링크를 반환합니다. |
| [getMedia()](#getMedia--) | 특수한 "play mediafile" 하이퍼링크를 반환합니다. |
| [getNextSlide()](#getNextSlide--) | 다음 슬라이드로 이동하는 하이퍼링크를 반환합니다. |
| [getPreviousSlide()](#getPreviousSlide--) | 이전 슬라이드로 이동하는 하이퍼링크를 반환합니다. |
| [getFirstSlide()](#getFirstSlide--) | 프레젠테이션의 첫 슬라이드로 이동하는 하이퍼링크를 반환합니다. |
| [getLastSlide()](#getLastSlide--) | 프레젠테이션의 마지막 슬라이드로 이동하는 하이퍼링크를 반환합니다. |
| [getLastVievedSlide()](#getLastVievedSlide--) | 마지막으로 본 슬라이드로 이동하는 하이퍼링크를 반환합니다. |
| [getEndShow()](#getEndShow--) | 쇼를 종료하는 하이퍼링크를 반환합니다. |
| [getActionType()](#getActionType--) | 하이퍼링크 작업 유형을 반환합니다. |
| [getExternalUrl()](#getExternalUrl--) | 외부 URL을 지정합니다. |
| [getTargetSlide()](#getTargetSlide--) | 하이퍼링크가 특정 슬라이드를 대상으로 하는 경우 해당 슬라이드를 반환합니다. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | 부분의 실제 내용과 무관하게 이 부분에 설정된 하이퍼링크를 나타냅니다. |
| [getTargetFrame()](#getTargetFrame--) | 부모 하이퍼링크의 대상이 존재할 경우, 부모 HTML 프레임셋 내의 프레임을 반환합니다. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | 부모 하이퍼링크의 대상이 존재할 경우, 부모 HTML 프레임셋 내의 프레임을 반환합니다. |
| [getTooltip()](#getTooltip--) | 부모 하이퍼링크와 연관되어 UI에 표시될 수 있는 문자열을 반환합니다. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | 부모 하이퍼링크와 연관되어 UI에 표시될 수 있는 문자열을 반환합니다. |
| [getHistory()](#getHistory--) | 부모 하이퍼링크의 대상이 호출될 때 조회된 하이퍼링크 목록에 추가될지 여부를 결정합니다. |
| [setHistory(boolean value)](#setHistory-boolean-) | 부모 하이퍼링크의 대상이 호출될 때 조회된 하이퍼링크 목록에 추가될지 여부를 결정합니다. |
| [getHighlightClick()](#getHighlightClick--) | 클릭 시 하이퍼링크를 강조 표시할지 여부를 결정합니다. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | 클릭 시 하이퍼링크를 강조 표시할지 여부를 결정합니다. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | 하이퍼링크 클릭 시 사운드를 중지할지 여부를 결정합니다. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | 하이퍼링크 클릭 시 사운드를 중지할지 여부를 결정합니다. |
| [getSound()](#getSound--) | 하이퍼링크의 재생 사운드를 나타냅니다. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | 하이퍼링크의 재생 사운드를 나타냅니다. |
| [getColorSource()](#getColorSource--) | 하이퍼링크 색상의 원본을 나타냅니다 - 스타일 또는 부분 형식. |
| [setColorSource(int value)](#setColorSource-int-) | 하이퍼링크 색상의 원본을 나타냅니다 - 스타일 또는 부분 형식. |
| [equals(Object obj)](#equals-java.lang.Object-) | 두 Hyperlink 인스턴스가 같은지 여부를 결정합니다. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | 두 Hyperlink 인스턴스가 같은지 여부를 결정합니다. |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | 두 하이퍼링크의 동등성을 테스트합니다. |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | 두 하이퍼링크의 불동등성을 테스트합니다. |
| [hashCode()](#hashCode--) | 해시 알고리즘 및 해시 테이블과 같은 데이터 구조에서 사용하기에 적합한 특정 타입에 대한 해시 함수 역할을 합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

하이퍼링크의 인스턴스를 생성합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| url | java.lang.String | 하이퍼링크 URL. |
### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

특정 슬라이드를 가리키는 하이퍼링크 인스턴스를 생성합니다. 참고: 생성된 하이퍼링크는 같은 프레젠테이션의 객체에 할당되어야 하며, 그렇지 않으면 링크가 NoAction으로 저장됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | 대상 슬라이드. |
### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

다른 하이퍼링크를 소스로 사용하고 보조 속성을 재정의하여 하이퍼링크의 인스턴스를 생성합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | 소스 하이퍼링크 |
| targetFrame | java.lang.String | 대상 프레임 |
| tooltip | java.lang.String | 툴팁 텍스트 |
| history | boolean | 부모 하이퍼링크의 대상이 호출될 때 조회된 하이퍼링크 목록에 추가될지 여부를 결정합니다. |
| stopSoundsOnClick | boolean | 하이퍼링크 클릭 시 사운드를 중지할지 여부를 결정합니다. |
| highlightClick | boolean | 클릭 시 하이퍼링크를 강조 표시할지 여부를 결정합니다. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

버전. 읽기 전용 long.

**반환값:**
long
### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

특수한 "do nothing" 하이퍼링크를 반환합니다. 읽기 전용 [Hyperlink](../../com.aspose.slides/hyperlink).

**반환값:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

특수한 "play mediafile" 하이퍼링크를 반환합니다. AudioFrame 및 VideoFrame에서 사용됩니다. 읽기 전용 [Hyperlink](../../com.aspose.slides/hyperlink).

**반환값:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

다음 슬라이드로 이동하는 하이퍼링크를 반환합니다. 읽기 전용 [Hyperlink](../../com.aspose.slides/hyperlink).

**반환값:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

이전 슬라이드로 이동하는 하이퍼링크를 반환합니다. 읽기 전용 [Hyperlink](../../com.aspose.slides/hyperlink).

**반환값:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

프레젠테이션의 첫 슬라이드로 이동하는 하이퍼링크를 반환합니다. 읽기 전용 [Hyperlink](../../com.aspose.slides/hyperlink).

**반환값:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

프레젠테이션의 마지막 슬라이드로 이동하는 하이퍼링크를 반환합니다. 읽기 전용 [Hyperlink](../../com.aspose.slides/hyperlink).

**반환값:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

마지막으로 본 슬라이드로 이동하는 하이퍼링크를 반환합니다. 읽기 전용 [Hyperlink](../../com.aspose.slides/hyperlink).

**반환값:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

쇼를 종료하는 하이퍼링크를 반환합니다. 읽기 전용 [Hyperlink](../../com.aspose.slides/hyperlink).

**반환값:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getActionType() {#getActionType--}
```
public final int getActionType()
```

하이퍼링크 작업 유형을 반환합니다. 읽기 전용 [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**반환값:**
int
### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

외부 URL을 지정합니다. 읽기 전용 String.

**반환값:**
java.lang.String
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

하이퍼링크가 특정 슬라이드를 대상으로 하는 경우 해당 슬라이드를 반환합니다. 읽기 전용 [ISlide](../../com.aspose.slides/islide).

**반환값:**
[ISlide](../../com.aspose.slides/islide)
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

부분의 실제 내용과 무관하게 이 부분에 설정된 하이퍼링크를 나타냅니다.

**반환값:**
java.lang.String
--------------------

PowerPoint는 링크와 해당 부분 텍스트에 대해 특수한 동작을 합니다. 유효한 URL 형식의 텍스트를 하이퍼링크로 만들 수 있으며, 이는 실제 주소와 다를 수 있습니다. 이 경우 편집 창에서 링크를 볼 때 텍스트 부분에 맞게 변경됩니다. 이 속성은 하이퍼링크의 원래 값을 나타냅니다.

**반환값:**
java.lang.String
### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

부모 하이퍼링크의 대상이 존재할 경우, 부모 HTML 프레임셋 내의 프레임을 반환합니다. 읽기/쓰기 String.

**반환값:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

부모 하이퍼링크의 대상이 존재할 경우, 부모 HTML 프레임셋 내의 프레임을 반환합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

부모 하이퍼링크와 연관되어 UI에 표시될 수 있는 문자열을 반환합니다. 읽기/쓰기 String.

**반환값:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

부모 하이퍼링크와 연관되어 UI에 표시될 수 있는 문자열을 반환합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

부모 하이퍼링크의 대상이 호출될 때 조회된 하이퍼링크 목록에 추가될지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

부모 하이퍼링크의 대상이 호출될 때 조회된 하이퍼링크 목록에 추가될지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

클릭 시 하이퍼링크를 강조 표시할지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

클릭 시 하이퍼링크를 강조 표시할지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

하이퍼링크 클릭 시 사운드를 중지할지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

하이퍼링크 클릭 시 사운드를 중지할지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getSound() {#getSound--}
```
public final IAudio getSound()
```

하이퍼링크의 재생 사운드를 나타냅니다. 읽기/쓰기 [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // 첫 번째 도형 하이퍼링크 가져오기
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // 바이트 배열로 하이퍼링크 사운드 추출
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**반환값:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

하이퍼링크의 재생 사운드를 나타냅니다. 읽기/쓰기 [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // 첫 번째 도형 하이퍼링크 가져오기
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // 바이트 배열로 하이퍼링크 사운드 추출
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getColorSource() {#getColorSource--}
```
public final int getColorSource()
```

하이퍼링크 색상의 원본을 나타냅니다 - 스타일 또는 부분 형식. 읽기/쓰기 [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**반환값:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

하이퍼링크 색상의 원본을 나타냅니다 - 스타일 또는 부분 형식. 읽기/쓰기 [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

두 Hyperlink 인스턴스가 같은지 여부를 결정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 현재 Hyperlink와 비교할 Hyperlink. |

**반환값:**
boolean - **true** if the specified Hyperlink is equal to the current Hyperlink; otherwise, **false**.
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

두 Hyperlink 인스턴스가 같은지 여부를 결정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | 현재 Hyperlink와 비교할 Hyperlink. |

**반환값:**
boolean - **true** if the specified Hyperlink is equal to the current Hyperlink; otherwise, **false**.
### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

두 하이퍼링크의 동등성을 테스트합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | 테스트할 첫 번째 하이퍼링크. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | 테스트할 두 번째 하이퍼링크. |

**반환값:**
boolean - **true** if hyperlinks are equal.
### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

두 하이퍼링크의 불동등성을 테스트합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | 테스트할 첫 번째 하이퍼링크. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | 테스트할 두 번째 하이퍼링크. |

**반환값:**
boolean - **false** if hyperlinks are equal.
### hashCode() {#hashCode--}
```
public int hashCode()
```

특정 타입에 대한 해시 함수 역할을 하며, 해시 알고리즘 및 해시 테이블과 같은 데이터 구조에서 사용하기에 적합합니다.

**반환값:**
int - URL에 대한 해시 코드.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환값:**
com.aspose.slides.IDOMObject