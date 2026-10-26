---
title: ISaveOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Options that control how a presentation is saved.
type: docs
url: /ko/com.aspose.slides/isaveoptions/
---```
public interface ISaveOptions
```

프레젠테이션을 저장하는 방식을 제어하는 옵션입니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | 경고를 수신하고 로드 프로세스를 계속할지 중단할지를 결정하는 객체를 반환하거나 설정합니다. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | 경고를 수신하고 로드 프로세스를 계속할지 중단할지를 결정하는 객체를 반환하거나 설정합니다. |
| [getProgressCallback()](#getProgressCallback--) | 백분율 단위로 저장 진행 상황 업데이트를 나타내는 콜백 객체입니다. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | 백분율 단위로 저장 진행 상황 업데이트를 나타내는 콜백 객체입니다. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | 소스 글꼴을 찾을 수 없는 경우 사용되는 글꼴을 반환하거나 설정합니다. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | 소스 글꼴을 찾을 수 없는 경우 사용되는 글꼴을 반환하거나 설정합니다. |
| [getGradientStyle()](#getGradientStyle--) | 그라디언트의 시각적 스타일을 반환하거나 설정합니다. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | 그라디언트의 시각적 스타일을 반환하거나 설정합니다. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | 프레젠테이션을 저장할 때 JavaScript 호출이 포함된 하이퍼링크를 건너뛸지 여부를 지정합니다. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | 프레젠테이션을 저장할 때 JavaScript 호출이 포함된 하이퍼링크를 건너뛸지 여부를 지정합니다. |
### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```


경고를 수신하고 로드 프로세스를 계속할지 중단할지를 결정하는 객체를 반환하거나 설정합니다. 읽기/쓰기 [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**반환값:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```


경고를 수신하고 로드 프로세스를 계속할지 중단할지를 결정하는 객체를 반환하거나 설정합니다. 읽기/쓰기 [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public abstract IProgressCallback getProgressCallback()
```


백분율 단위로 저장 진행 상황 업데이트를 나타내는 콜백 객체입니다. [IProgressCallback](../../com.aspose.slides/iprogresscallback)를 참조하십시오.

**반환값:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public abstract void setProgressCallback(IProgressCallback value)
```


백분율 단위로 저장 진행 상황 업데이트를 나타내는 콜백 객체입니다. [IProgressCallback](../../com.aspose.slides/iprogresscallback)를 참조하십시오.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```


소스 글꼴을 찾을 수 없는 경우 사용되는 글꼴을 반환하거나 설정합니다. 읽기/쓰기 String.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try
>  {
>      HtmlOptions htmlOpts = new HtmlOptions();
>      htmlOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.html", SaveFormat.Html, htmlOpts);
>      htmlOpts.setDefaultRegularFont("Lucida Console");
>      pres.save("Somepresentation-out-LucidaConsole.html", SaveFormat.Html, htmlOpts);
>      PdfOptions pdfOpts = new PdfOptions();
>      pdfOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.pdf", SaveFormat.Pdf, pdfOpts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환값:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```


소스 글꼴을 찾을 수 없는 경우 사용되는 글꼴을 반환하거나 설정합니다. 읽기/쓰기 String.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try
>  {
>      HtmlOptions htmlOpts = new HtmlOptions();
>      htmlOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.html", SaveFormat.Html, htmlOpts);
>      htmlOpts.setDefaultRegularFont("Lucida Console");
>      pres.save("Somepresentation-out-LucidaConsole.html", SaveFormat.Html, htmlOpts);
>      PdfOptions pdfOpts = new PdfOptions();
>      pdfOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.pdf", SaveFormat.Pdf, pdfOpts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getGradientStyle() {#getGradientStyle--}
```
public abstract int getGradientStyle()
```


그라디언트의 시각적 스타일을 반환하거나 설정합니다. 읽기/쓰기 [GradientStyle](../../com.aspose.slides/gradientstyle).

**반환값:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public abstract void setGradientStyle(int value)
```


그라디언트의 시각적 스타일을 반환하거나 설정합니다. 읽기/쓰기 [GradientStyle](../../com.aspose.slides/gradientstyle).

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public abstract boolean getSkipJavaScriptLinks()
```


프레젠테이션을 저장할 때 JavaScript 호출이 포함된 하이퍼링크를 건너뛸지 여부를 지정합니다. 읽기/쓰기 boolean. 기본값은 false입니다.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      HtmlOptions htmlOptions = new HtmlOptions();
>      htmlOptions.setSkipJavaScriptLinks(true);
>      pres.save("result_without_JavaScript_links.html", SaveFormat.Html, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

이 속성을 true로 설정하면 저장 중에 JavaScript 호출이 포함된 하이퍼링크가 무시됩니다.

이 속성을 false로 설정하면 모든 하이퍼링크가 저장됩니다.

**반환값:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public abstract void setSkipJavaScriptLinks(boolean value)
```


프레젠테이션을 저장할 때 JavaScript 호출이 포함된 하이퍼링크를 건너뛸지 여부를 지정합니다. 읽기/쓰기 boolean. 기본값은 false입니다.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      HtmlOptions htmlOptions = new HtmlOptions();
>      htmlOptions.setSkipJavaScriptLinks(true);
>      pres.save("result_without_JavaScript_links.html", SaveFormat.Html, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

이 속성을 true로 설정하면 저장 중에 JavaScript 호출이 포함된 하이퍼링크가 무시됩니다.

이 속성을 false로 설정하면 모든 하이퍼링크가 저장됩니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | boolean |  |