---
title: WebDocument
second_title: Aspose.Slides for Android용 Java API 참조
description: 프레젠테이션을 웹 형식으로 저장하기 위한 전환 형태를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/webdocument/
---
**상속:**  
java.lang.Object  
```
public class WebDocument
```

프레젠테이션을 웹 형식으로 저장하기 위한 전환 형태를 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [WebDocument(WebDocumentOptions options)](#WebDocument-com.aspose.slides.WebDocumentOptions-) | [WebDocument](../../com.aspose.slides/webdocument) 생성자. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [save()](#save--) | 문서 출력을 저장합니다. |
| [getInput()](#getInput--) | 문서의 입력 요소(템플릿) 컬렉션을 반환합니다. |
| [getOutput()](#getOutput--) | 문서의 출력 요소 컬렉션을 반환합니다. |
| [getGlobal()](#getGlobal--) | 문서의 전역 저장소를 반환합니다. |

### WebDocument(WebDocumentOptions options) {#WebDocument-com.aspose.slides.WebDocumentOptions-}
```
public WebDocument(WebDocumentOptions options)
```

[WebDocument](../../com.aspose.slides/webdocument) 생성자.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [WebDocumentOptions](../../com.aspose.slides/webdocumentoptions) | 문서에 설정된 옵션입니다. |

### save() {#save--}
```
public final void save()
```

문서 출력을 저장합니다.

### getInput() {#getInput--}
```
public final Input getInput()
```

문서의 입력 요소(템플릿) 컬렉션을 반환합니다. 읽기 전용 [Input](../../com.aspose.slides/input)(#getInput.getInput).

**반환값:**
[Input](../../com.aspose.slides/input)

### getOutput() {#getOutput--}
```
public final Output getOutput()
```

문서의 출력 요소 컬렉션을 반환합니다. 읽기 전용 [Output](../../com.aspose.slides/output)(#getOutput.getOutput).

--------------------

> ```
> WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // "slideMargin" 속성을 템플릿에서 사용하기 위해 넣습니다
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... 문서의 다른 옵션들을 설정하고 나서 문서를 저장합니다
>   document.save();
> ```

**반환값:**
[Output](../../com.aspose.slides/output)

### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```

문서의 전역 저장소를 반환합니다. 읽기 전용 [Storage](../../com.aspose.slides/storage).

--------------------

> ```
> Using this (#getGlobal.getGlobal) property (implementation of [Storage](../../com.aspose.slides/storage) interface) a
>   property can be put to use it later in the template:
>   
>   WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // "slideMargin" 속성을 템플릿에서 사용하기 위해 넣습니다
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... 문서의 다른 옵션들을 설정하고 나서 문서를 저장합니다
>   document.save();
> ```

**반환값:**
[Storage](../../com.aspose.slides/storage)