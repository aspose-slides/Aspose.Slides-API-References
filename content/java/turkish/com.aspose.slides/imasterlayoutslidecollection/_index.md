---
title: IMasterLayoutSlideCollection
second_title: Aspose.Slides için Java API Referansı
description: Tanımlı ana slaydın tüm yerleşim slaytlarını içeren bir koleksiyonu temsil eder.
type: docs
url: /tr/com.aspose.slides/imasterlayoutslidecollection/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IMasterLayoutSlideCollection extends ILayoutSlideCollection
```

Tanımlı ana slaydın tüm yerleşim slaytlarını içeren bir koleksiyonu temsil eder. ILayoutSlideCollection arayüzünü, ana slaydın yerleşim slaytları koleksiyonları bağlamında ekleme, ekleme konumuna yerleştirme, kaldırma ve klonlama metotlarıyla genişletir.

## Metotlar

| Metot | Açıklama |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Belirtilen bir yerleşim slaydının bir kopyasını koleksiyonun sonuna ekler. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Belirtilen bir yerleşim slaydının bir kopyasını koleksiyonun belirtilen konumuna ekler. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Yeni bir yerleşim slaydını koleksiyonun sonuna ekler. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Yeni bir yerleşim slaydını koleksiyonun belirtilen konumuna ekler. |
| [removeAt(int index)](#removeAt-int-) | Koleksiyonun belirtilen indeksindeki öğeyi kaldırır. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Yerleşim slaydını koleksiyondan belirtilen konuma taşır. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Belirtilen bir yerleşim slaydının bir kopyasını koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Klonlanacak slayt.

--------------------

1) Yeni yerleşim, bu yerleşim slaytları koleksiyonu için ana slaydın ebeveyniyle bağlanacaktır. Bu, PowerPoint’te “Use Destination Theme” seçeneğiyle yapılan kopyala/yapıştır işleminin eşdeğeridir. 2) Bu metodun eşdeğeri, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) metodu ve [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides) özelliği ile erişilir.

**Döndürür:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Eklenen slayt.

### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Belirtilen bir yerleşim slaydının bir kopyasını koleksiyonun belirtilen konumuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni slaydın indeksi. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Klonlanacak slayt.

--------------------

Yeni yerleşim, bu yerleşim slaytları koleksiyonu için ana slaydın ebeveyniyle bağlanacaktır. Bu, PowerPoint’te “Use Destination Theme” seçeneğiyle yapılan kopyala/yapıştır işleminin eşdeğeridir.

**Döndürür:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Eklenen slayt.

### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public abstract ILayoutSlide add(byte layoutType, String layoutName)
```

Yeni bir yerleşim slaydını koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| layoutType | byte | Yeni bir yerleşim için düzen tipi. Desteklenen düzen tipleri: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Şu anda desteklenmeyen diğer düzen tipleri: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Yeni bir düzenin adı. Verilen ad zaten kullanılıyorsa ArgumentException fırlatılır. Null parametre verilirse, verilen düzen tipine göre otomatik olarak bir ad oluşturulur (örneğin “Title Slide” ya da “1_Title Slide”, “2_..” vb.). |

--------------------

1) layoutType değeri SlideLayoutType.Custom olan eklenen düzen, yer tutucu ve şekil içermez. 2) Bu metodun eşdeğeri, [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) metodu ve [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides) özelliği ile erişilir.

**Döndürür:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Eklenen slayt.

### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public abstract ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Yeni bir yerleşim slaydını koleksiyonun belirtilen konumuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni slaydın indeksi. |
| layoutType | byte | Yeni bir yerleşim için düzen tipi. Desteklenen düzen tipleri: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Şu anda desteklenmeyen diğer düzen tipleri: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Yeni bir düzenin adı. Verilen ad zaten kullanılıyorsa ArgumentException fırlatılır. Null parametre verilirse, verilen düzen tipine göre otomatik olarak bir ad oluşturulur (örneğin “Title Slide” ya da “1_Title Slide”, “2_..” vb.). |

--------------------

layoutType değeri SlideLayoutType.Custom olan eklenen düzen, yer tutucu ve şekil içermez.

**Döndürür:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Eklenen slayt.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Koleksiyonun belirtilen indeksindeki öğeyi kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak öğenin sıfır tabanlı indeksi.

--------------------

1) PptxEditException fırlatılmasını önlemek için önce düzenin HasDependingSlides özelliğini kontrol edin. 2) Kodu basitleştirmek için ayrıca [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) metodunu da kullanabilirsiniz.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public abstract void reorder(int index, ILayoutSlide layoutSlide)
```

Yerleşim slaydını koleksiyondan belirtilen konuma taşır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Hedef indeks. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Taşınacak slayt. |