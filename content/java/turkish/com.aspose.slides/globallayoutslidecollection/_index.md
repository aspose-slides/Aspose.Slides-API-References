---
title: GlobalLayoutSlideCollection
second_title: Aspose.Slides için Java API Referansı
description: Sunumdaki tüm düzen slaytlarının bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/globallayoutslidecollection/
---
**Kalıtım:** 
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**Uygulanan Tüm Arayüzler:** 
[com.aspose.slides.IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
```
public final class GlobalLayoutSlideCollection extends LayoutSlideCollection implements IGlobalLayoutSlideCollection
```

Sunumdaki tüm düzen slaytlarının bir koleksiyonunu temsil eder. LayoutSlideCollection sınıfını genişleterek, master'ın düzen slaytlarının bireysel koleksiyonlarını birleştirme bağlamında düzen slaytlarını ekleme/kopyalama yöntemleri sağlar.
## Yöntemler

| Metod | Açıklama |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Belirtilen bir düzen slaytının bir kopyasını sunuma ekler. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Belirtilen bir düzen slaytının bir kopyasını sunuma ekler. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Sunuma yeni bir düzen slaytı ekler. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```


Belirtilen bir düzen slaytının bir kopyasını sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Klonlanacak slayt. |

--------------------

Farklı sunumlar arasında bir düzeni kopyalarken düzenin master'ı da kaynak biçimlendirmesini korumak için kopyalanabilir. İç kayıt defteri, otomatik olarak kopyalanan master'ları izlemek ve aynı master slaytının birden çok kopyasının oluşturulmasını önlemek için kullanılır. Master slaytların manuel kopyalanması ne önlenir ne de kaydedilir. |

**Döndürür:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Eklenen slayt.
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```


Belirtilen bir düzen slaytının bir kopyasını sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Klonlanacak slayt. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Yeni bir düzen için master slayt. |

--------------------

1) Yeni bir düzen, hedef sunumdaki tanımlı master ile ilişkilendirilecektir. Bu, PowerPoint'teki "Use Destination Theme" seçeneğiyle yapılan kopyala/yapıştır işleminin bir benzeridir. 2) Bu yöntemin analogu, [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-) yöntemi olup ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) özelliği ile erişilir. |

**Döndürür:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Eklenen slayt.
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```


Sunuma yeni bir düzen slaytı ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Yeni bir düzen için master slayt. |
| layoutType | byte | Yeni bir düzen için düzen türü. Desteklenen düzen türleri: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Şu anda desteklenmeyen diğer düzen türleri: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Yeni bir düzen için ad. Geçilen ad zaten kullanımdaysa ArgumentException fırlatılacaktır. Null parametre geçirilirse, ad geçilen düzen tipine göre otomatik olarak oluşturulur (örneğin "Title Slide" ya da "1_Title Slide", "2_..", vb.). |

--------------------

1) layoutType değeri SlideLayoutType.Custom olan eklenen düzen, yer tutucu ve şekil içermez. 2) Bu yöntemin analogu, [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) yöntemi olup ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) özelliği ile erişilir. |

**Döndürür:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Eklenen slayt.