---
title: IGlobalLayoutSlideCollection
second_title: Aspose.Slides for Android via Java API Referansı
description: Sunumdaki tüm yerleşim slaytlarını içeren bir koleksiyonu temsil eder.
type: docs
url: /tr/com.aspose.slides/igloballayoutslidecollection/
---
**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

Sunumdaki tüm yerleşim slaytlarını içeren bir koleksiyonu temsil eder. Tekil ana yerleşim slaytı koleksiyonlarını birleştirme bağlamında yerleşim slaytlarını ekleme/kopyalama yöntemleri sağlayan ILayoutSlideCollection arabirimini genişletir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Belirtilen yerleşim slaytının bir kopyasını sunuma ekler. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Belirtilen yerleşim slaytının bir kopyasını sunuma ekler. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Sunuma yeni bir yerleşim slaytı ekler. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Belirtilen yerleşim slaytının bir kopyasını sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Kopyalanacak slayt.

--------------------

Farklı sunumlar arasında bir yerleşim kopyalanırken, kaynağın biçimlendirmesini korumak için yerleşimin master slaytı da kopyalanabilir. Aynı master slaytının birden fazla kopyasının oluşturulmasını önlemek için dahili bir kayıt defteri otomatik olarak kopyalanan masterları izler. Master slaytların elle kopyalanması ne önlenir ne de kaydedilir. |

**Dönüş Değeri:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Eklenen slayt.
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

Belirtilen yerleşim slaytının bir kopyasını sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Kopyalanacak slayt. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Yeni yerleşim için master slayt.

--------------------

Yeni yerleşim, hedef sunumda tanımlı master ile ilişkilendirilecektir. Bu, PowerPoint'te “Use Destination Theme” seçeneğiyle yapılan kopyala/yapıştır işleminin benzeridir. |

**Dönüş Değeri:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Eklenen slayt.
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

Sunuma yeni bir yerleşim slaytı ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Yeni yerleşim için master slayt. |
| layoutType | byte | Yeni yerleşim için yerleşim tipi. Desteklenen yerleşim tipleri: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Şu anda desteklenmeyen diğer yerleşim tipleri: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Yeni yerleşim için ad. Aynı ad zaten kullanılıyorsa ArgumentException fırlatılır. Null parametre geçilirse, verilen yerleşim tipine göre (örneğin “Title Slide” veya “1_Title Slide”, “2_…” vb.) otomatik olarak bir ad üretilir. |

--------------------

1) layoutType değeri SlideLayoutType.Custom olduğu zaman eklenen yerleşim hiçbir yer tutucu ve şekil içermez. 2) Bu yöntemin analogu, ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) özelliğiyle erişilebilen [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) yöntemidir. |

**Dönüş Değeri:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Eklenen slayt.