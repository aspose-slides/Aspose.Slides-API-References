---
title: SlideUtil
second_title: Aspose.Slides for Android Java API Referansı
description: Bir sunumda şekilleri ve metni aramaya yardımcı yöntemler sunar.
type: docs
url: /tr/com.aspose.slides/slideutil/
---
**Kalıtım:**
java.lang.Object
```
public class SlideUtil
```

Sunumda şekilleri ve metni aramaya yardımcı olan yöntemler sunar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SlideUtil()](#SlideUtil--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [findShape(IPresentation pres, String altText)](#findShape-com.aspose.slides.IPresentation-java.lang.String-) | Bir PPTX sunumunda alternatif metne göre şekil bulur. |
| [findShape(IBaseSlide slide, String altText)](#findShape-com.aspose.slides.IBaseSlide-java.lang.String-) | Bir PPTX sunumunda bir slaytta alternatif metne göre şekil bulur. |
| [findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)](#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-) | Belirtilen slaytta verilen yer tutucu türüyle eşleşen tüm şekilleri arar. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-) | Slayttaki tüm şekillerin konumunu değiştirir. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---) | Seçilen şekillerin slayttaki konumunu değiştirir. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-) | Grup şekli içindeki tüm şekillerin konumunu değiştirir. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---) | Grup şekli içindeki seçilen şekillerin konumunu değiştirir. |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) | Sunumda metni verilen formatla bulur ve değiştirir. |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-) | Sunumda metni verilen formatla bulur ve değiştirir. |
| [getAllTextBoxes(IBaseSlide slide)](#getAllTextBoxes-com.aspose.slides.IBaseSlide-) | Bir PPTX sunumundaki bir slayttaki tüm metin çerçevelerini döndürür. |
| [getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)](#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-) | Belirtilen slaytta verilen metni içeren tüm metin çerçevelerini döndürür. |
| [getAllTextFrames(IPresentation pres, boolean withMasters)](#getAllTextFrames-com.aspose.slides.IPresentation-boolean-) | Bir PPTX sunumundaki tüm metin çerçevelerini döndürür. |
| [toSaveFormat(int format)](#toSaveFormat-int-) | Bir kaynak dosya formatını karşılık gelen [SaveFormat](../../com.aspose.slides/saveformat)'ye dönüştürür. |
### SlideUtil() {#SlideUtil--}
```
public SlideUtil()
```


### findShape(IPresentation pres, String altText) {#findShape-com.aspose.slides.IPresentation-java.lang.String-}
```
public static IShape findShape(IPresentation pres, String altText)
```

Bir PPTX sunumunda alternatif metne göre şekil bulur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Taranan sunum. |
| altText | java.lang.String | Bir şeklin alternatif metni. |

**Döndürür:**
[IShape](../../com.aspose.slides/ishape) - Şekil veya null.
### findShape(IBaseSlide slide, String altText) {#findShape-com.aspose.slides.IBaseSlide-java.lang.String-}
```
public static IShape findShape(IBaseSlide slide, String altText)
```

Bir PPTX sunumunda bir slaytta alternatif metne göre şekil bulur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Taranan slayt. |
| altText | java.lang.String | Bir şeklin alternatif metni. |

**Döndürür:**
[IShape](../../com.aspose.slides/ishape) - Şekil veya null.
### findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType) {#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-}
```
public static IShape[] findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)
```

Belirtilen slaytta verilen yer tutucu türüyle eşleşen tüm şekilleri arar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Şekillerin aranacağı slayt. |
| placeholderType | byte | Filtrelenecek yer tutucu tipi. |

**Döndürür:**
com.aspose.slides.IShape[] - Belirtilen yer tutucu tipine uyan [IShape](../../com.aspose.slides/ishape) nesnelerinin bir dizisi.
### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)
```

Slayttaki tüm şekillerin konumunu değiştirir. Şekilleri kenarlara veya slayt kenarına hizalar ya da birbirlerine göre hizalar.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignBottom, true, pres.getSlides().get_Item(0));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| alignmentType | int | Hangi hizalama türünün uygulanacağını belirler. |
| alignToSlide | boolean | Doğruysa, şekiller slayt kenarlarına göre hizalanır. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Üst slayt. |

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)
```

Seçilen şekillerin slayttaki konumunu değiştirir. Şekilleri kenarlara veya slayt kenarına hizalar ya da birbirlerine göre hizalar.

--------------------

> ```
> Example:
>   
>   Presentation pres = new Presentation("pres.pptx");
>   try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IShape shape1 = slide.getShapes().get_Item(0);
>      IShape shape2 = slide.getShapes().get_Item(1);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignBottom, false, pres.getSlides().get_Item(0), new int[]
>      {
>          slide.getShapes().indexOf(shape1),
>          slide.getShapes().indexOf(shape2)
>      });
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| alignmentType | int | Hangi hizalama türünün uygulanacağını belirler. |
| alignToSlide | boolean | Doğruysa, şekiller slayt kenarlarına göre hizalanır. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Üst slayt. |
| shapeIndexes | int[] | Hizalanacak şekillerin indeksleri. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)
```

Grup şekli içindeki tüm şekillerin konumunu değiştirir. Şekilleri kenarlara veya slayt kenarına hizalar ya da birbirlerine göre hizalar.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape) slide.getShapes().get_Item(0));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| alignmentType | int | Hangi hizalama türünün uygulanacağını belirler. |
| alignToSlide | boolean | Doğruysa, şekiller slayt kenarlarına göre hizalanır. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Üst grup şekli. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)
```

Grup şekli içindeki seçilen şekillerin konumunu değiştirir. Şekilleri kenarlara veya slayt kenarına hizalar ya da birbirlerine göre hizalar.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.getShapes().get_Item(0), new int[] { 0, 2 });
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| alignmentType | int | Hangi hizalama türünün uygulanacağını belirler. |
| alignToSlide | boolean | Doğruysa, şekiller slayt kenarlarına göre hizalanır. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Üst grup şekli. |
| shapeIndexes | int[] | Hizalanacak şekillerin indeksleri. |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)
```

Sunumda metni verilen formatla bulur ve değiştirir.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PortionFormat format = new PortionFormat();
>      format.setFontHeight(24f);
>      format.setFontItalic(NullableBool.True);
>      format.getFillFormat().setFillType(FillType.Solid);
>      format.getFillFormat().getSolidFillColor().setColor(Color.RED);
> 
>      SlideUtil.findAndReplaceText(pres, true, "[this block] ", "my text ", format);
>      pres.save("replaced.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Taranan sunum. |
| withMasters | boolean | Üst slaytların taranıp taranmayacağını belirler. |
| find | java.lang.String | Bulunacak dize değeri. |
| replace | java.lang.String | Değiştirilecek dize değeri. Bulunan dize karakteri |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)
```

Sunumda metni verilen formatla bulur ve değiştirir.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PortionFormat format = new PortionFormat();
>      format.setFontHeight(24f);
>      format.setFontItalic(NullableBool.True);
>      format.getFillFormat().setFillType(FillType.Solid);
>      format.getFillFormat().getSolidFillColor().setColor(Color.RED);
> 
>      SlideUtil.findAndReplaceText(pres, true, "[this block] ", "my text ", format);
>      pres.save("replaced.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Taranan sunum. |
| withMasters | boolean | Üst slaytların taranıp taranmayacağını belirler. |
| find | java.lang.String | Bulunacak dize değeri. |
| replace | java.lang.String | Değiştirilecek dize değeri. |
| format | [PortionFormat](../../com.aspose.slides/portionformat) | Metin bölümünü değiştirmek için format. Null ise bulunan dizedeki ilk karakterin formatı kullanılacak. |

### getAllTextBoxes(IBaseSlide slide) {#getAllTextBoxes-com.aspose.slides.IBaseSlide-}
```
public static ITextFrame[] getAllTextBoxes(IBaseSlide slide)
```

Bir PPTX sunumundaki bir slayttaki tüm metin çerçevelerini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Taranan slayt. |

**Döndürür:**
com.aspose.slides.ITextFrame[] - [TextFrame](../../com.aspose.slides/textframe) nesnelerinin bir dizisi.
### getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText) {#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-}
```
public static ITextFrame[] getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)
```

Belirtilen slaytta verilen metni içeren tüm metin çerçevelerini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Aranacak slayt. |
| text | java.lang.String | Metin çerçevelerinde aranacak metin. |
| checkPlaceholderText | boolean | Metin çerçevesi boş olsa da, yer tutucu metni aranan metni içeriyorsa dahil edilip edilmeyeceğini belirtir. |

**Döndürür:**
com.aspose.slides.ITextFrame[] - Belirtilen metni içeren [ITextFrame](../../com.aspose.slides/itextframe) nesnelerinin bir dizisi.
### getAllTextFrames(IPresentation pres, boolean withMasters) {#getAllTextFrames-com.aspose.slides.IPresentation-boolean-}
```
public static ITextFrame[] getAllTextFrames(IPresentation pres, boolean withMasters)
```

Bir PPTX sunumundaki tüm metin çerçevelerini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Taranan sunum. |
| withMasters | boolean | Üst slaytların taranıp taranmayacağını belirler. |

**Döndürür:**
com.aspose.slides.ITextFrame[] - [TextFrame](../../com.aspose.slides/textframe) nesnelerinin bir dizisi.
### toSaveFormat(int format) {#toSaveFormat-int-}
```
public static int toSaveFormat(int format)
```

Bir kaynak dosya formatını karşılık gelen [SaveFormat](../../com.aspose.slides/saveformat)'e dönüştürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| format | int | Kaynak dosya formatı. |

**Döndürür:**
int - Karşılık gelen [SaveFormat](../../com.aspose.slides/saveformat) değeri.