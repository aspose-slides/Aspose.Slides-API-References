---
title: MasterLayoutSlideCollection
second_title: Aspose.Slides for Java API Referansı
description: Tanımlı ana slaydın tüm düzen slaytlarını içeren bir koleksiyonu temsil eder.
type: docs
url: /tr/com.aspose.slides/masterlayoutslidecollection/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
```
public final class MasterLayoutSlideCollection extends LayoutSlideCollection implements IMasterLayoutSlideCollection
```

Tanımlı ana slaydın tüm düzen slaytlarını içeren bir koleksiyonu temsil eder. LayoutSlideCollection sınıfını, ana slaydın düzen slaytlarının bireysel koleksiyonları bağlamında ekleme/kopyalama/kaldırma/kopyalama/yeniden sıralama yöntemleriyle genişletir.
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
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Belirtilen bir düzen slaytının bir kopyasını koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Klonlanacak slayt. |

--------------------

1) Yeni düzen, bu düzen slaytları koleksiyonu için ana slaydla bağlanacaktır. Bu nedenle PowerPoint'teki "Use Destination Theme" seçeneğiyle kopyala/yapıştır işleminin bir analoğudur. 2) Bu yöntemin analoğu, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) yöntemi ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) özelliğiyle erişilen. |

**Döndürür:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Eklenen slayt.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Belirtilen bir düzen slaytının bir kopyasını koleksiyonun belirtilen konumuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni slayt indeksi. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Klonlanacak slayt. |

--------------------

Yeni düzen, bu düzen slaytları koleksiyonu için ana slaydla bağlanacaktır. Bu nedenle PowerPoint'teki "Use Destination Theme" seçeneğiyle kopyala/yapıştır işleminin bir analoğudur. |

**Döndürür:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Ekleme yapılan slayt.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public final ILayoutSlide add(byte layoutType, String layoutName)
```

Yeni bir düzen slaytını koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| layoutType | byte | Yeni bir düzen için düzen tipi. Desteklenen düzen tipleri: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Yeni bir düzenin adı. Verilen ad zaten kullanılıyorsa ArgumentException fırlatılır. Null parametre geçirilirse, verilen düzen tipine göre otomatik olarak (örneğin "Title Slide" veya "1_Title Slide", "2_.." vb.) isim oluşturulur. |

--------------------

1) layoutType değeri SlideLayoutType.Custom olan eklenen düzen, hiçbir yer tutucu ve şekil içermez. 2) Bu yöntemin analoğu, [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) yöntemi ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) özelliğiyle erişilen. |

**Döndürür:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Eklenen slayt.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public final ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Yeni bir düzen slaytını koleksiyonun belirtilen konumuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni slayt indeksi. |
| layoutType | byte | Yeni bir düzen için düzen tipi. Desteklenen düzen tipleri: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Yeni bir düzenin adı. Verilen ad zaten kullanılıyorsa ArgumentException fırlatılır. Null parametre geçirilirse, verilen düzen tipine göre otomatik olarak (örneğin "Title Slide" veya "1_Title Slide", "2_.." vb.) isim oluşturulur. |

--------------------

layoutType değeri SlideLayoutType.Custom olan eklenen düzen, hiçbir yer tutucu ve şekil içermez. |

**Döndürür:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Ekleme yapılan slayt.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Koleksiyonun belirtilen indeksteki öğeyi kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak öğenin sıfır tabanlı indeksi. |

--------------------

1) PptxEditException oluşumunu önlemek için layout'un HasDependingSlides özelliğini önceden kontrol edin. 2) Kodu basitleştirmek için ayrıca [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) yöntemini de kullanabilirsiniz. |
### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```

Düzen slaytını koleksiyondan belirtilen konuma taşır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Hedef indeks. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Taşınacak slayt. |