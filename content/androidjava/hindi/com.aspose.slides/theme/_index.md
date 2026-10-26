---
title: Theme
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: एक थीम का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/theme/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme), com.aspose.slides.IStyleColorOwner, com.aspose.slides.IPVIObject
```
public abstract class Theme implements ITheme, IStyleColorOwner, IPVIObject
```

एक थीम का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | रंग योजना लौटाता है। |
| [getFontScheme()](#getFontScheme--) | फ़ॉन्ट योजना लौटाता है। |
| [getFormatScheme()](#getFormatScheme--) | आकार फॉर्मेट योजना लौटाता है। |
| [getPresentation()](#getPresentation--) | पैरेंट प्रस्तुति लौटाता है। |
| [getEffective()](#getEffective--) | विरासत लागू करके प्रभावी थीम डेटा प्राप्त करता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```


रंग योजना लौटाता है। केवल पढ़ने योग्य [IColorScheme](../../com.aspose.slides/icolorscheme).

**वापसी:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```


फ़ॉन्ट योजना लौटाता है। केवल पढ़ने योग्य [IFontScheme](../../com.aspose.slides/ifontscheme).

**वापसी:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```


आकार फॉर्मेट योजना लौटाता है। केवल पढ़ने योग्य [IFormatScheme](../../com.aspose.slides/iformatscheme).

**वापसी:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


पैरेंट प्रस्तुति लौटाता है। केवल पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation).

**वापसी:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getEffective() {#getEffective--}
```
public final IThemeEffectiveData getEffective()
```


विरासत लागू करके प्रभावी थीम डेटा प्राप्त करता है।

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

**वापसी:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - A [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य IDOMObject.

**वापसी:**
com.aspose.slides.IDOMObject
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


पैरेंट IPresentationComponent लौटाता है। केवल पढ़ने योग्य [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**वापसी:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getVersion() {#getVersion--}
```
public abstract long getVersion()
```


संस्करण। केवल पढ़ने योग्य long.

**वापसी:**
long