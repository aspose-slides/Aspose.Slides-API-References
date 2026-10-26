---
title: IHyperlink
second_title: Aspose.Slides for Java API Reference
description: Represents a hyperlink.
type: docs
url: /ko/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

하이퍼링크를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getActionType()](#getActionType--) | HyperLinkEx의 동작 유형을 반환합니다. |
| [getExternalUrl()](#getExternalUrl--) | 외부 URL을 지정합니다. 이 속성이 null이 아니게 되면 TargetSlide 속성은 null이 됩니다. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | 부분의 실제 내용과 무관하게 이 부분에 설정된 하이퍼링크를 나타냅니다. |
| [getTargetSlide()](#getTargetSlide--) | HyperlinkEx가 특정 슬라이드를 대상으로 하면 해당 슬라이드를 반환합니다. |
| [getTargetFrame()](#getTargetFrame--) | 존재하는 경우, 부모 하이퍼링크 대상에 대한 부모 HTML 프레임셋 내의 프레임을 반환합니다. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | 존재하는 경우, 부모 하이퍼링크 대상에 대한 부모 HTML 프레임셋 내의 프레임을 반환합니다. |
| [getTooltip()](#getTooltip--) | 부모 하이퍼링크와 연관되어 사용자 인터페이스에 표시될 수 있는 문자열을 반환합니다. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | 부모 하이퍼링크와 연관되어 사용자 인터페이스에 표시될 수 있는 문자열을 반환합니다. |
| [getHistory()](#getHistory--) | 호출될 때 부모 하이퍼링크의 대상이 조회된 하이퍼링크 목록에 추가될지 여부를 결정합니다. |
| [setHistory(boolean value)](#setHistory-boolean-) | 호출될 때 부모 하이퍼링크의 대상이 조회된 하이퍼링크 목록에 추가될지 여부를 결정합니다. |
| [getHighlightClick()](#getHighlightClick--) | 클릭 시 하이퍼링크를 강조 표시할지 여부를 결정합니다. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | 클릭 시 하이퍼링크를 강조 표시할지 여부를 결정합니다. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | 하이퍼링크 클릭 시 사운드를 중지할지 여부를 결정합니다. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | 하이퍼링크 클릭 시 사운드를 중지할지 여부를 결정합니다. |
| [getSound()](#getSound--) | 하이퍼링크의 재생 중인 사운드를 나타냅니다. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | 하이퍼링크의 재생 중인 사운드를 나타냅니다. |
| [getColorSource()](#getColorSource--) | 하이퍼링크 색상의 출처를 나타냅니다 - 스타일 또는 부분 형식 중 하나. |
| [setColorSource(int value)](#setColorSource-int-) | 하이퍼링크 색상의 출처를 나타냅니다 - 스타일 또는 부분 형식 중 하나. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | 두 Hyperlink 인스턴스가 같은지 여부를 결정합니다. |
### getActionType() {#getActionType--}
```
public abstract int getActionType()
```


HyperLinkEx의 동작 유형을 반환합니다. 읽기 전용 [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**반환:**  
int
### getExternalUrl() {#getExternalUrl--}
```
public abstract String getExternalUrl()
```


외부 URL을 지정합니다. 이 속성이 null이 아니게 되면 TargetSlide 속성은 null이 됩니다. 읽기 전용 String.

**반환:**  
java.lang.String
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public abstract String getExternalUrlOriginal()
```


PowerPoint은 부분에 있는 링크와 해당 텍스트에 대해 특별히 동작합니다. 실제 링크 주소와 다른 유효한 URL 형태의 텍스트를 하이퍼링크로 생성할 수 있습니다. 이 경우 편집 창에서 링크를 보면 텍스트 부분에 맞게 변경됩니다. 이 속성은 하이퍼링크의 원래 값을 나타냅니다.

**반환:**  
java.lang.String
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```


HyperlinkEx가 특정 슬라이드를 대상으로 하면 해당 슬라이드를 반환합니다. 이 속성이 null이 아니게 되면 ExternalUrl 속성은 null이 됩니다. 읽기 전용 [ISlide](../../com.aspose.slides/islide).

**반환:**  
[ISlide](../../com.aspose.slides/islide)
### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```


존재하는 경우, 부모 하이퍼링크 대상에 대한 부모 HTML 프레임셋 내의 프레임을 반환합니다. 읽기/쓰기 String.

**반환:**  
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```


존재하는 경우, 부모 하이퍼링크 대상에 대한 부모 HTML 프레임셋 내의 프레임을 반환합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```


부모 하이퍼링크와 연관되어 사용자 인터페이스에 표시될 수 있는 문자열을 반환합니다. 읽기/쓰기 String.

**반환:**  
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```


부모 하이퍼링크와 연관되어 사용자 인터페이스에 표시될 수 있는 문자열을 반환합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```


호출될 때 부모 하이퍼링크의 대상이 조회된 하이퍼링크 목록에 추가될지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**  
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```


호출될 때 부모 하이퍼링크의 대상이 조회된 하이퍼링크 목록에 추가될지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```


클릭 시 하이퍼링크를 강조 표시할지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**  
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```


클릭 시 하이퍼링크를 강조 표시할지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```


하이퍼링크 클릭 시 사운드를 중지할지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**  
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```


하이퍼링크 클릭 시 사운드를 중지할지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```


하이퍼링크의 재생 중인 사운드를 나타냅니다. 읽기/쓰기 [IAudio](../../com.aspose.slides/iaudio).

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
>          // 하이퍼링크 사운드를 바이트 배열로 추출
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**반환:**  
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```


하이퍼링크의 재생 중인 사운드를 나타냅니다. 읽기/쓰기 [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Get the first shape hyperlink
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extract the hyperlink sound in byte array
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
public abstract int getColorSource()
```


하이퍼링크 색상의 출처를 나타냅니다 - 스타일 또는 부분 형식 중 하나. 읽기/쓰기 [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**반환:**  
int
### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```


하이퍼링크 색상의 출처를 나타냅니다 - 스타일 또는 부분 형식 중 하나. 읽기/쓰기 [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public abstract boolean equals(IHyperlink hlink)
```


두 Hyperlink 인스턴스가 같은지 여부를 결정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | 비교 대상 Hyperlink. |

**반환:**  
boolean - **true** if the specified Hyperlink is equal to the current Hyperlink; otherwise, **false**.