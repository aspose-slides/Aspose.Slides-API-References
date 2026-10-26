---
title: Theme
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 테마를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/theme/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme), com.aspose.slides.IStyleColorOwner, com.aspose.slides.IPVIObject  
```
public abstract class Theme implements ITheme, IStyleColorOwner, IPVIObject
```

테마를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | 색 구성표를 반환합니다. |
| [getFontScheme()](#getFontScheme--) | 글꼴 구성표를 반환합니다. |
| [getFormatScheme()](#getFormatScheme--) | 도형 형식 구성표를 반환합니다. |
| [getPresentation()](#getPresentation--) | 부모 프레젠테이션을 반환합니다. |
| [getEffective()](#getEffective--) | 상속이 적용된 효과적인 테마 데이터를 가져옵니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```

색 구성표를 반환합니다. 읽기 전용 [IColorScheme](../../com.aspose.slides/icolorscheme).

**반환:**  
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```

글꼴 구성표를 반환합니다. 읽기 전용 [IFontScheme](../../com.aspose.slides/ifontscheme).

**반환:**  
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```

도형 형식 구성표를 반환합니다. 읽기 전용 [IFormatScheme](../../com.aspose.slides/iformatscheme).

**반환:**  
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

부모 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../com.aspose.slides/ipresentation).

**반환:**  
[IPresentation](../../com.aspose.slides/ipresentation)
### getEffective() {#getEffective--}
```
public final IThemeEffectiveData getEffective()
```

상속이 적용된 효과적인 테마 데이터를 가져옵니다.

--------------------

> ```
> This example demonstrates getting effective theme properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IThemeEffectiveData effectiveTheme  = pres.getSlides().get_Item(0).getThemeManager().getOverrideTheme().getEffective();
>  	System.out.println("Font scheme name: " + effectiveTheme.getFontScheme().getName());
>  	System.out.println("Major latin font: " + effectiveTheme.getFontScheme().getMajor().getLatinFont().getFontName());
>  	System.out.println("Minor latin font: " + effectiveTheme.getFontScheme().getMinor().getLatinFont().getFontName());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**반환:**  
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - 하나의 [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환:**  
com.aspose.slides.IDOMObject
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

IPresentationComponent를 반환합니다. 읽기 전용 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**반환:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getVersion() {#getVersion--}
```
public abstract long getVersion()
```

버전. 읽기 전용 long.

**반환:**  
long