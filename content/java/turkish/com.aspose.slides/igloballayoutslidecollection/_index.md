---
title: IGlobalLayoutSlideCollection
second_title: Aspose.Slides for Java API Referansı
description: Sunumdaki tüm yerleşim slaytlarını içeren bir koleksiyon temsil eder.
type: docs
url: /tr/com.aspose.slides/igloballayoutslidecollection/
---
**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

Sunumdaki tüm yerleşim slaytlarını içeren bir koleksiyon temsil eder. ILayoutSlideCollection arabirimini, tek tek ana yerleşim slaytlarının koleksiyonlarını birleştirme bağlamında yerleşim slaytlarını ekleme/kopyalama yöntemleriyle genişletir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Belirtilen bir yerleşim slaytının bir kopyasını sunuma ekler. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Belirtilen bir yerleşim slaytının bir kopyasını sunuma ekler. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Sunuma yeni bir yerleşim slaytı ekler. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```


Belirtilen bir yerleşim slaytının bir kopyasını sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Klonlanacak slayt. |

--------------------

Farklı sunumlar arasında bir yerleşim klonlanırken, kaynağın biçimini korumak için yerleşimin ana slaytı da klonlanabilir. Aynı ana slaytın birden çok klonunun oluşturulmasını önlemek için otomatik olarak klonlanan ana slaytları izleyen iç kayıt defteri kullanılır. Ana slaytların manuel klonlanması ne engellenir ne de kaydedilir. |

**Dönüş Değeri:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Eklenen slayt.
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```


Belirtilen bir yerleşim slaytının bir kopyasını sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Klonlanacak slayt. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Yeni bir yerleşim için ana slayt. |

--------------------

Yeni yerleşim, hedef sunumda tanımlı ana slayt ile bağlantılandırılacaktır. Bu, PowerPoint’te “Use Destination Theme” seçeneğiyle yapılan kopyala/yapıştır işleminin bir benzeri gibidir. |

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
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Yeni bir yerleşim için ana slayt. |
| layoutType | byte | Yeni bir yerleşim için düzen türü. Desteklenen düzen türleri: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Şu an desteklenmeyen diğer düzen türleri: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Yeni bir yerleşim için ad. Verilen ad zaten kullanılıyorsa ArgumentException fırlatılır. Eğer null parametre verilirse, ad, verilen düzen türüne göre otomatik olarak oluşturulur (örneğin "Title Slide" veya "1_Title Slide", "2_.." vb.). |

--------------------

1) layoutType değeri SlideLayoutType.Custom olan eklenen yerleşim, hiçbir yer tutucu ve şekil içermez. 2) Bu yöntemin benzeri, [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) yöntemi ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) özelliğiyle erişilen yöntemdir. |

**Dönüş Değeri:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Eklenen slayt.