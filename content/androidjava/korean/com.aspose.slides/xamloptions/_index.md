---
title: XamlOptions
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: XAML 문서가 저장되는 방식을 제어하는 옵션.
type: docs
url: /ko/com.aspose.slides/xamloptions/
---
**Inheritance:**  
상속:  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**  
구현된 모든 인터페이스:  
[com.aspose.slides.IXamlOptions](../../com.aspose.slides/ixamloptions)  
```
public class XamlOptions extends SaveOptions implements IXamlOptions
```

Options that control how a XAML document is saved.  
XAML 문서를 저장하는 방식을 제어하는 옵션.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [XamlOptions()](#XamlOptions--) | XamlOptions 인스턴스를 생성합니다. |
## Methods

| Method | Description |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | 숨겨진 슬라이드가 내보내질지 여부를 결정합니다. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | 숨겨진 슬라이드가 내보내질지 여부를 결정합니다. |
| [getOutputSaver()](#getOutputSaver--) | IOutputSaver 인터페이스의 구현을 나타냅니다. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | IOutputSaver 인터페이스의 구현을 나타냅니다. |
### XamlOptions() {#XamlOptions--}
```
public XamlOptions()
```

XamlOptions 인스턴스를 생성합니다.

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```

숨겨진 슬라이드가 내보내질지 여부를 결정합니다.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**  
반환값:  
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```

숨겨진 슬라이드가 내보내질지 여부를 결정합니다.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**  
매개변수:
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOutputSaver() {#getOutputSaver--}
```
public final IXamlOutputSaver getOutputSaver()
```

IOutputSaver 인터페이스의 구현을 나타냅니다.

**Returns:**  
반환값:  
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public final void setOutputSaver(IXamlOutputSaver value)
```

IOutputSaver 인터페이스의 구현을 나타냅니다.

**Parameters:**  
매개변수:
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |