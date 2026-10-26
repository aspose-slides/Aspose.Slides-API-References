---
title: GlobalLayoutSlideCollection
second_title: Aspose.Slides for Android, Java API Referansı aracılığıyla
description: Sunumdaki tüm yerleşim slaytlarını içeren bir koleksiyonu temsil eder.
type: docs
url: /tr/com.aspose.slides/globallayoutslidecollection/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
```
public final class GlobalLayoutSlideCollection extends LayoutSlideCollection implements IGlobalLayoutSlideCollection
```

Sunumda bulunan tüm yerleşim slaytlarını içeren bir koleksiyon temsil eder. LayoutSlideCollection sınıfını, tek tek ana yerleşim slaytlarının koleksiyonlarını birleştirme bağlamında yerleşim slaytlarını ekleme/kopyalama (klonlama) yöntemleriyle genişletir.
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Belirtilen bir yerleşim slaytının bir kopyasını sunuma ekler. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Belirtilen bir yerleşim slaytının bir kopyasını sunuma ekler. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Yeni bir yerleşim slaytı sunuma ekler. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```


Belirtilen bir yerleşim slaytının bir kopyasını sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Klonlanacak slayt.

--------------------

Farklı sunumlar arasında bir yerleşim klonlanırken, kaynak biçimlendirmeyi korumak için yerleşimin master'ı da klonlanabilir. İç kayıt, otomatik olarak klonlanan master'ları izlemek ve aynı master slaytının birden çok klonunun oluşturulmasını önlemek için kullanılır. Master slaytların manuel klonlanması ne engellenir ne de kayıt altına alınır.

**Döndürür:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Eklenen slayt.
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```


Belirtilen bir yerleşim slaytının bir kopyasını sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Klonlanacak slayt. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Yeni bir yerleşim için master slayt.

--------------------

1) Yeni yerleşim, hedef sunumda tanımlı master ile ilişkilendirilecektir. Bu nedenle PowerPoint'te "Use Destination Theme" seçeneğiyle yapılan kopyala/yapıştır işleminin bir benzeri olarak düşünülebilir. 2) Bu yöntemin analogu, ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) özelliğiyle erişilen [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-) yöntemidir. |

**Döndürür:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Eklenen slayt.
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```


Yeni bir yerleşim slaytı sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Yeni bir yerleşim için master slayt. |
| layoutType | byte | Yeni bir yerleşim için layout türü. Desteklenen layout türleri: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Şu anda desteklenmeyen diğer layout türleri: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Yeni bir yerleşim için ad. Eğer verilen ad zaten kullanılıyorsa ArgumentException fırlatılır. Eğer null parametresi verilirse, ad, verilen layout türüne göre otomatik olarak oluşturulur (örneğin "Title Slide" veya "1_Title Slide", "2_.." gibi). |

--------------------

1) layoutType değeri SlideLayoutType.Custom olduğu durum için eklenen yerleşim, hiçbir yer tutucu ve şekil içermez. 2) Bu yöntemin analogu, ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) özelliğiyle erişilen [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) yöntemidir. |

**Döndürür:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Eklenen slayt.