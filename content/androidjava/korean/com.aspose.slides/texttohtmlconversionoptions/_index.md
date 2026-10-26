---
title: TextToHtmlConversionOptions
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: Pptx 텍스트에서 HTML을 추출하기 위한 옵션.
type: docs
url: /ko/com.aspose.slides/texttohtmlconversionoptions/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions)  
```
public final class TextToHtmlConversionOptions implements ITextToHtmlConversionOptions
```

Pptx 텍스트에서 HTML을 추출하기 위한 옵션.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [TextToHtmlConversionOptions()](#TextToHtmlConversionOptions--) |  |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | 클립보드 헤더를 추가할지 여부를 나타내는 값을 반환하거나 설정합니다. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | 클립보드 헤더를 추가할지 여부를 나타내는 값을 반환하거나 설정합니다. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | 텍스트 속성에 대한 상속 깊이를 반환하거나 설정합니다. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | 텍스트 속성에 대한 상속 깊이를 반환하거나 설정합니다. |
| [getLinkEmbedController()](#getLinkEmbedController--) | 외부 객체가 저장되는 방식을 제어하는 콜백 객체를 반환하거나 설정합니다. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | 외부 객체가 저장되는 방식을 제어하는 콜백 객체를 반환하거나 설정합니다. |
| [getEncodingName()](#getEncodingName--) | HTML 인코딩 이름을 반환하거나 설정합니다. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | HTML 인코딩 이름을 반환하거나 설정합니다. |

### TextToHtmlConversionOptions() {#TextToHtmlConversionOptions--}
```
public TextToHtmlConversionOptions()
```

### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public final boolean getAddClipboardFragmentHeader()
```

클립보드 헤더를 추가할지 여부를 나타내는 값을 반환하거나 설정합니다. 읽기/쓰기 boolean.

**반환값:**  
boolean

### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public final void setAddClipboardFragmentHeader(boolean value)
```

클립보드 헤더를 추가할지 여부를 나타내는 값을 반환하거나 설정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public final int getTextInheritanceLimit()
```

텍스트 속성에 대한 상속 깊이를 반환하거나 설정합니다. 읽기/쓰기 [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**반환값:**  
int

### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public final void setTextInheritanceLimit(int value)
```

텍스트 속성에 대한 상속 깊이를 반환하거나 설정합니다. 읽기/쓰기 [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public final ILinkEmbedController getLinkEmbedController()
```

외부 객체가 저장되는 방식을 제어하는 콜백 객체를 반환하거나 설정합니다. 읽기/쓰기 [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**반환값:**  
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)

### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public final void setLinkEmbedController(ILinkEmbedController value)
```

외부 객체가 저장되는 방식을 제어하는 콜백 객체를 반환하거나 설정합니다. 읽기/쓰기 [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public final String getEncodingName()
```

HTML 인코딩 이름을 반환하거나 설정합니다. 이 값은 생성된 HTML 파일에 저장되지만, 파일이 해당 인코딩으로 저장되도록 보장하는 것은 호출자에게 달려 있습니다. 읽기/쓰기 String.

**반환값:**  
java.lang.String

### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public final void setEncodingName(String value)
```

HTML 인코딩 이름을 반환하거나 설정합니다. 이 값은 생성된 HTML 파일에 저장되지만, 파일이 해당 인코딩으로 저장되도록 보장하는 것은 호출자에게 달려 있습니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |