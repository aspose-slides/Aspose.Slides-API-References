---
title: IMasterLayoutSlideCollection
second_title: Aspose.Slides Android için Java API Referansı
description: Tanımlı ana slaydın tüm düzen slaytlarını içeren bir koleksiyonu temsil eder.
type: docs
url: /tr/com.aspose.slides/imasterlayoutslidecollection/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IMasterLayoutSlideCollection extends ILayoutSlideCollection
```

Tanımlı ana slaytın tüm düzen slaytlarını içeren bir koleksiyonu temsil eder. ILayoutSlideCollection arayüzünü, ana slaydın düzen slaytları koleksiyonları bağlamında ekleme/ekleme/çıkarma/kopyalama yöntemleriyle genişletir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Belirtilen bir düzen slaytının bir kopyasını koleksiyonun sonuna ekler. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Belirtilen bir düzen slaytının bir kopyasını koleksiyonun belirtilen konumuna ekler. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Yeni bir düzen slaytını koleksiyonun sonuna ekler. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Yeni bir düzen slaytını koleksiyonun belirtilen konumuna ekler. |
| [removeAt(int index)](#removeAt-int-) | Koleksiyonun belirtilen indeksteki öğeyi kaldırır. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Düzen slaytını koleksiyondan belirtilen konuma taşır. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Belirtilen bir düzen slaytının bir kopyasını koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Klonlanacak slayt.

--------------------

1) Yeni düzen, bu düzen slaytları koleksiyonu için üst ana slaytla bağlanacaktır. Bu, PowerPoint'te "Use Destination Theme" seçeneğiyle yapılan kopyala/yapıştırın bir benzeridir. 2) Bu yöntemin analoğu, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) yöntemi olup [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides) özelliğiyle erişilir. 

**Dönüş Değeri:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Eklenen slayt.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Belirtilen bir düzen slaytının bir kopyasını koleksiyonun belirtilen konumuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni slaytın indeksi. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Klonlanacak slayt.

--------------------

Yeni düzen, bu düzen slaytları koleksiyonu için üst ana slaytla bağlanacaktır. Bu, PowerPoint'te "Use Destination Theme" seçeneğiyle yapılan kopyala/yapıştırın bir benzeridir. 

**Dönüş Değeri:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Eklenen slayt.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public abstract ILayoutSlide add(byte layoutType, String layoutName)
```

Yeni bir düzen slaytını koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| layoutType | byte | Yeni bir düzen için düzen türü. Desteklenen düzen türleri: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Şu anda desteklenmeyen diğer düzen türleri: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Yeni bir düzen için ad. Verilen ad zaten kullanılıyorsa ArgumentException fırlatılır. Null parametre verilirse, verilen düzen türüne göre (örnek "Title Slide" veya "1_Title Slide", "2_..", vb.) otomatik olarak bir ad oluşturulur. |

--------------------

1) layoutType değeri SlideLayoutType.Custom olan eklenen düzen, yer tutucu ve şekil içermez. 2) Bu yöntemin analoğu, [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) yöntemi olup [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides) özelliğiyle erişilir. 

**Dönüş Değeri:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Eklenen slayt.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public abstract ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Yeni bir düzen slaytını koleksiyonun belirtilen konumuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni slaytın indeksi. |
| layoutType | byte | Yeni bir düzen için düzen türü. Desteklenen düzen türleri: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Şu anda desteklenmeyen diğer düzen türleri: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Yeni bir düzen için ad. Verilen ad zaten kullanılıyorsa ArgumentException fırlatılır. Null parametre verilirse, verilen düzen türüne göre (örnek "Title Slide" veya "1_Title Slide", "2_..", vb.) otomatik olarak bir ad oluşturulur. |

--------------------

layoutType değeri SlideLayoutType.Custom olan eklenen düzen, yer tutucu ve şekil içermez. 

**Dönüş Değeri:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Eklenen slayt.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Koleksiyonun belirtilen indeksteki öğeyi kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak öğenin sıfır tabanlı indeksi.

--------------------

1) PptxEditException hatasının önlenmesi için düzenin HasDependingSlides özelliği önceden kontrol edilmelidir. 2) Kodu basitleştirmek için [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) yöntemi de kullanılabilir. 

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public abstract void reorder(int index, ILayoutSlide layoutSlide)
```

Düzen slaytını koleksiyondan belirtilen konuma taşır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Hedef indeks. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Taşınacak slayt. |