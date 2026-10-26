---
title: IXamlOptions
second_title: Android용 Aspose.Slides Java API 레퍼런스
description: XAML 문서가 저장되는 방식을 제어하는 옵션.
type: docs
url: /ko/com.aspose.slides/ixamloptions/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXamlOptions extends ISaveOptions
```

Options that control how a XAML document is saved.

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

## 메서드

| Method | Description |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | 숨겨진 슬라이드가 내보내질지 여부를 결정합니다. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | 숨겨진 슬라이드가 내보내질지 여부를 결정합니다. |
| [getOutputSaver()](#getOutputSaver--) | IOutputSaver 인터페이스의 구현을 나타냅니다. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | IOutputSaver 인터페이스의 구현을 나타냅니다. |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
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

**반환값:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public abstract void setExportHiddenSlides(boolean value)
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

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getOutputSaver() {#getOutputSaver--}
```
public abstract IXamlOutputSaver getOutputSaver()
```


IOutputSaver 인터페이스의 구현을 나타냅니다.

**반환값:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public abstract void setOutputSaver(IXamlOutputSaver value)
```


IOutputSaver 인터페이스의 구현을 나타냅니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |