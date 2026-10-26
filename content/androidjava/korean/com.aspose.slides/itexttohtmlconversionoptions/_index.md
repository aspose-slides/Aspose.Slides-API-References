---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Pptx 텍스트에서 HTML을 추출하기 위한 옵션.
type: docs
url: /ko/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

Pptx 텍스트에서 HTML을 추출하기 위한 옵션.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | 값을 반환하거나 설정합니다. Clipboard 헤더를 추가할지 여부를 나타냅니다. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | 값을 반환하거나 설정합니다. Clipboard 헤더를 추가할지 여부를 나타냅니다. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | 값을 반환하거나 설정합니다. 텍스트 속성에 대한 상속 깊이를 지정합니다. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | 값을 반환하거나 설정합니다. 텍스트 속성에 대한 상속 깊이를 지정합니다. |
| [getLinkEmbedController()](#getLinkEmbedController--) | 값을 반환하거나 설정합니다. 외부 객체가 저장되는 방식을 제어하는 콜백 객체를 반환하거나 설정합니다. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | 값을 반환하거나 설정합니다. 외부 객체가 저장되는 방식을 제어하는 콜백 객체를 반환하거나 설정합니다. |
| [getEncodingName()](#getEncodingName--) | 값을 반환하거나 설정합니다. html 인코딩 이름을 지정합니다. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | 값을 반환하거나 설정합니다. html 인코딩 이름을 지정합니다. |
### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```

값을 반환하거나 설정합니다. Clipboard 헤더를 추가할지 여부를 나타냅니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```

값을 반환하거나 설정합니다. Clipboard 헤더를 추가할지 여부를 나타냅니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```

값을 반환하거나 설정합니다. 텍스트 속성에 대한 상속 깊이를 지정합니다. 읽기/쓰기 [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**반환값:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```

값을 반환하거나 설정합니다. 텍스트 속성에 대한 상속 깊이를 지정합니다. 읽기/쓰기 [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```

값을 반환하거나 설정합니다. 외부 객체가 저장되는 방식을 제어하는 콜백 객체를 반환하거나 설정합니다. 읽기/쓰기 [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**반환값:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```

값을 반환하거나 설정합니다. 외부 객체가 저장되는 방식을 제어하는 콜백 객체를 반환하거나 설정합니다. 읽기/쓰기 [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |
### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```

값을 반환하거나 설정합니다. html 인코딩 이름을 지정합니다. 이 값은 생성된 HTML 파일에 저장되지만 파일이 해당 인코딩으로 저장되도록 호출자가 보장해야 합니다. 읽기/쓰기 String.

**반환값:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```

값을 반환하거나 설정합니다. html 인코딩 이름을 지정합니다. 이 값은 생성된 HTML 파일에 저장되지만 파일이 해당 인코딩으로 저장되도록 호출자가 보장해야 합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |