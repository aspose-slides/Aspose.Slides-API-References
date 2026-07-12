---
title: MasterLayoutSlideCollection
second_title: Java API Referansı aracılığıyla Aspose.Slides for Android
description: Tanımlı ana slaytın tüm yerleşim slaytlarını içeren bir koleksiyonu temsil eder.
type: docs
url: /tr/com.aspose.slides/masterlayoutslidecollection/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
```
public final class MasterLayoutSlideCollection extends LayoutSlideCollection implements IMasterLayoutSlideCollection
```

Tanımlı ana slaytın tüm yerleşim slaytlarını içeren bir koleksiyonu temsil eder. LayoutSlideCollection sınıfını genişletir ve ana slaytın yerleşim slaytlarının bireysel koleksiyonları bağlamında yerleşim slaytlarını ekleme/ekleme/kaldırma/kopyalama/yeniden sıralama yöntemlerini sağlar.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Belirtilen yerleşim slaytının bir kopyasını koleksiyonun sonuna ekler. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Belirtilen yerleşim slaytının bir kopyasını koleksiyonun belirtilen konumuna ekler. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Yeni bir yerleşim slaytını koleksiyonun sonuna ekler. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Yeni bir yerleşim slaytını koleksiyonun belirtilen konumuna ekler. |
| [removeAt(int index)](#removeAt-int-) | Koleksiyonun belirtilen dizinindeki öğeyi kaldırır. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Yerleşim slaytını koleksiyondan belirtilen konuma taşır. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```


Belirtilen yerleşim slaytının bir kopyasını koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Kopyalanacak slayt.

--------------------

1) Yeni yerleşim, bu yerleşim slaytları koleksiyonu için üst ana slayt ile bağlantılı olur. Bu, PowerPoint'te “Use Destination Theme” seçeneğiyle yapılan kopyala/yapıştır işleminin benzeridir. 2) Bu yöntemin benzeri, ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) özelliğiyle erişilen [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) yöntemidir. |

**Döndürür:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Eklenen slayt.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```


Belirtilen yerleşim slaytının bir kopyasını koleksiyonun belirtilen konumuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni slaytın dizini. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Kopyalanacak slayt.

--------------------

Yeni yerleşim, bu yerleşim slaytları koleksiyonu için üst ana slayt ile bağlantılı olur. Bu, PowerPoint'te “Use Destination Theme” seçeneğiyle yapılan kopyala/yapıştır işleminin benzeridir. |

**Döndürür:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Eklenen slayt.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public final ILayoutSlide add(byte layoutType, String layoutName)
```


Yeni bir yerleşim slaytını koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| layoutType | byte | Yeni yerleşim için yerleşim tipi. Desteklenen tipler: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Şu anda desteklenmeyen tipler: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Yeni yerleşim için ad. Aynı ad zaten kullanılıyorsa ArgumentException fırlatılır. null geçirilirse, verilen yerleşim tipine göre (örneğin "Title Slide" ya da "1_Title Slide", "2_..") otomatik olarak ad oluşturulur.

--------------------

1) layoutType değeri SlideLayoutType.Custom olduğunda eklenen yerleşim hiçbir yer tutucu ve şekil içermez. 2) Bu yöntemin benzeri, ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) özelliğiyle erişilen [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) yöntemidir. |

**Döndürür:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Eklenen slayt.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public final ILayoutSlide insert(int index, byte layoutType, String layoutName)
```


Yeni bir yerleşim slaytını koleksiyonun belirtilen konumuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni slaytın dizini. |
| layoutType | byte | Yeni yerleşim için yerleşim tipi. Desteklenen tipler: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Şu anda desteklenmeyen tipler: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Yeni yerleşim için ad. Aynı ad zaten kullanılıyorsa ArgumentException fırlatılır. null geçirilirse, verilen yerleşim tipine göre (örneğin "Title Slide" ya da "1_Title Slide", "2_..") otomatik olarak ad oluşturulur.

--------------------

layoutType değeri SlideLayoutType.Custom olduğunda eklenen yerleşim hiçbir yer tutucu ve şekil içermez. |

**Döndürür:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Eklenen slayt.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Koleksiyonun belirtilen dizinindeki öğeyi kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak öğenin sıfır tabanlı dizini.

--------------------

1) PptxEditException hatasının önüne geçmek için önceden layout'ın HasDependingSlides özelliği kontrol edilmelidir. 2) Kodu basitleştirmek için [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) yöntemi de kullanılabilir. |

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```


Yerleşim slaytını koleksiyondan belirtilen konuma taşır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Hedef dizin. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Taşınacak slayt. |