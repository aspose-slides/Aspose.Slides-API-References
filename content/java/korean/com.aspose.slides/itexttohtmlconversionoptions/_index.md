---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Java API Reference
description: PPTX 텍스트에서 HTML을 추출하기 위한 옵션.
type: docs
url: /ko/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

PPTX 텍스트에서 HTML을 추출하기 위한 옵션.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Clipboard 헤더를 추가할지 여부를 나타내는 값을 반환하거나 설정합니다. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Clipboard 헤더를 추가할지 여부를 나타내는 값을 반환하거나 설정합니다. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | 텍스트 속성에 대한 상속 깊이를 반환하거나 설정합니다. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | 텍스트 속성에 대한 상속 깊이를 반환하거나 설정합니다. |
| [getLinkEmbedController()](#getLinkEmbedController--) | 외부 객체가 저장되는 방식을 제어하는 콜백 객체를 반환하거나 설정합니다. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | 외부 객체가 저장되는 방식을 제어하는 콜백 객체를 반환하거나 설정합니다. |
| [getEncodingName()](#getEncodingName--) | HTML 인코딩 이름을 반환하거나 설정합니다. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | HTML 인코딩 이름을 반환하거나 설정합니다. |
### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```

Clipboard 헤더를 추가할지 여부를 나타내는 값을 반환하거나 설정합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```

Clipboard 헤더를 추가할지 여부를 나타내는 값을 반환하거나 설정합니다. 읽기/쓰기 boolean.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```

텍스트 속성에 대한 상속 깊이를 반환하거나 설정합니다. 읽기/쓰기 [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**반환:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```

텍스트 속성에 대한 상속 깊이를 반환하거나 설정합니다. 읽기/쓰기 [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```

외부 객체가 저장되는 방식을 제어하는 콜백 객체를 반환하거나 설정합니다. 읽기/쓰기 [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**반환:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```

외부 객체가 저장되는 방식을 제어하는 콜백 객체를 반환하거나 설정합니다. 읽기/쓰기 [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |
### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```

HTML 인코딩 이름을 반환하거나 설정합니다. 이 값은 생성된 HTML 파일에 저장되지만, 파일이 해당 인코딩으로 저장되도록 보장하는 것은 호출자에게 달려 있습니다. 읽기/쓰기 String.

**반환:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```

HTML 인코딩 이름을 반환하거나 설정합니다. 이 값은 생성된 HTML 파일에 저장되지만, 파일이 해당 인코딩으로 저장되도록 보장하는 것은 호출자에게 달려 있습니다. 읽기/쓰기 String.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |