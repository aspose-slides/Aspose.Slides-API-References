---
title: OleObjectFrame
second_title: Aspose.Sildes için .NET API Referansı
description: Bir slayt üzerindeki OLE nesnesini temsil eder.
type: docs
weight: 9210
url: /tr/aspose.slides/oleobjectframe/
---
## OleObjectFrame sınıfı

Bir slaytta OLE nesnesini temsil eder.

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Bir şekille ilişkili alternatif metni alır veya ayarlar. Okunur/Yazılabilir String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Bir şekille ilişkili alternatif metnin başlığını alır veya ayarlar. Okunur/Yazılabilir String. |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | Temel IGraphicalObject arayüzünü almayı sağlar. Yalnızca-okunur [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Şeklin siyah-beyaz görüntü modunda nasıl render edileceğini belirten özelliktir. Okunur/Yazılabilir [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Şeklin bağlantı noktası sayısını döndürür. Yalnızca-okunur Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Şeklin özel verilerini döndürür. Yalnızca-okunur [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Bir şekle uygulanmış piksel efektlerini içeren EffectFormat nesnesini döndürür. Not: efekt özelliği olmayan bazı şekil türleri için null dönebilir. Yalnızca-okunur [`IEffectFormat`](../ieffectformat). |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | OLE gömülü verileriyle ilgili bilgileri alır veya ayarlar. Okunur/Yazılabilir [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | Gömülü OLE nesnesinin dosya adını döndürür. |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | Gömülü OLE nesnesinin yolunu döndürür. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Bir şeklin dolgu biçimlendirme özelliklerini içeren FillFormat nesnesini döndürür. Not: dolgu özelliği olmayan bazı şekil türleri için null dönebilir. Yalnızca-okunur [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Şekil çerçevesinin özelliklerini alır veya ayarlar. Okunur/Yazılabilir [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Şeklin kilitlerini döndürür. Yalnızca-okunur [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Şeklin yüksekliğini, nokta cinsinden alır veya ayarlar. Okunur/Yazılabilir Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Şeklin gizli olup olmadığını belirler. Okunur/Yazılabilir Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Fare tıklamasına tanımlı köprüyi alır veya ayarlar. Okunur/Yazılabilir [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Köprü yöneticisini döndürür. Yalnızca-okunur [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Fare üzerindeyken tanımlı köprüyü alır veya ayarlar. Okunur/Yazılabilir [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘Dekoratif olarak işaretle’ seçeneğini alır veya ayarlar. Okunur/Yazılabilir Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Şeklin gruplanıp gruplanmadığını belirler. Yalnızca-okunur Boolean. |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | Nesnenin simge olarak görünüp görünmediğini belirler. Okunur/Yazılabilir Boolean. |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | Nesnenin harici bir dosyaya bağlı olup olmadığını belirler. Yalnızca-okunur Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Şeklin TextHolder_PPT olup olmadığını belirler. Yalnızca-okunur Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Bir şeklin çizgi biçimlendirme özelliklerini içeren LineFormat nesnesini döndürür. Not: çizgi özelliği olmayan bazı şekil türleri için null dönebilir. Yalnızca-okunur [`ILineFormat`](../ilineformat). |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | Bağlı bir dosyanın tam yolunu döndürür. Kısa dosya adı kullanılacaktır. Yalnızca-okunur String. |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | Bağlı bir dosyanın tam yolunu döndürür. Uzun dosya adı kullanılacaktır. Okunur/Yazılabilir String. |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | Bağlı bir dosyanın göreli yolunu döndürür; yoksa boş dize döner. Yalnızca-okunur String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Şeklin adını alır veya ayarlar. Boş olmayacak şekilde ayarlanmalıdır. Gerekirse boş dize kullanılabilir. Okunur/Yazılabilir String. |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | Nesnenin adını alır veya ayarlar. Okunur/Yazılabilir String. |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | Nesnenin ProgID’sini döndürür. Yalnızca-okunur String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Şekil ömür boyu sabit kalan, slayt kapsamlı benzersiz tanımlayıcısını döndürür; böylece PowerPoint veya interop kodu şekle her yerden güvenilir biçimde başvurabilir. Yalnızca-okunur UInt32. Ayrıca bakınız [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Şekil gruplanmışsa üst GroupShape nesnesini döndürür. Aksi takdirde null döner. Yalnızca-okunur [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Şeklin yer tutucusunu döndürür. Yer tutucu yoksa null döner. Yalnızca-okunur [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Slayın ana sunum nesnesini döndürür. Yalnızca-okunur [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Ham şekil çerçevesinin özelliklerini alır veya ayarlar. Okunur/Yazılabilir [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Belirtilen şeklin z-ekseni etrafında döndürüldüğü derece sayısını alır veya ayarlar. Pozitif değer saat yönünde, negatif değer saat yönünün tersine döndürür. Okunur/Yazılabilir Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Şeklin kilitlerini döndürür. Yalnızca-okunur [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 özellik) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Şeklin üst slaydını döndürür. Yalnızca-okunur [`IBaseSlide`](../ibaseslide). |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | OleObject resim dolgu özellikleri nesnesini döndürür. Yalnızca-okunur [`IPictureFillFormat`](../ipicturefillformat). |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | OleObject simgesi için başlığı alır veya ayarlar. Okunur/Yazılabilir String. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Şeklin 3D efekt özelliklerini içeren ThreeDFormat nesnesini döndürür. Not: 3D özelliği olmayan bazı şekil türleri için null dönebilir. Yalnızca-okunur [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Eklentiler veya diğer kodlar tarafından kullanılmak üzere, sunuma özgü iç kimliği döndürür. Bu değer kullanıcı veya program tarafından yeniden atanabileceği için kalıcı bir benzersiz anahtar olarak kullanılmamalıdır. Yalnızca-okunur UInt32. Ayrıca bakınız [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | Bağlı gömülü nesnenin sunum açıldığında veya yazdırıldığında otomatik olarak güncellenip güncellenmeyeceğini belirler. Okunur/Yazılabilir Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Şeklin genişliğini, nokta cinsinden alır veya ayarlar. Okunur/Yazılabilir Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Şeklin sol-üst köşesinin x koordinatını, nokta cinsinden alır veya ayarlar. Okunur/Yazılabilir Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Şeklin sol-üst köşesinin y koordinatını, nokta cinsinden alır veya ayarlar. Okunur/Yazılabilir Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Şeklin z-sırasındaki konumunu döndürür. Shapes[0] z-sırasının arkasındaki şekli, Shapes[Shapes.Count - 1] ise önündeki şekli verir. Yalnızca-okunur Int32. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Hiç placeholder yoksa yeni bir placeholder ekler ve placeholder özelliklerini belirtilenine ayarlar. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Temel bir placeholder şekli döndürür (geçerli şeklin miras aldığı düzen ve/veya ana slayttan). Geçerli şekil miras alınmamışsa null döner. |
| [GetImage](../../aspose.slides/shape/getimage)() | Şekil küçük resmini döndürür. Varsayılan olarak ShapeThumbnailBounds.Shape kullanılır. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Şekil küçük resmini döndürür. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Şeklin render edilen içeriğinden hesaplanan görsel sınırlarını alır. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Bu şeklin placeholder olmadığını tanımlar. |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | OLE gömülü veri bilgilerini ayarlar. Bu yöntem, nesnenin özelliklerini yeni veriyi yansıtacak şekilde değiştirir ve IsObjectLink bayrağını false yapar; böylece OLE nesnesi gömülüdür. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Şeklin içeriğini SVG dosyası olarak kaydeder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Şeklin içeriğini SVG dosyası olarak kaydeder. |

### Örnekler

Aşağıdaki örnek, OLE Nesne çerçevelerine nasıl erişileceğini gösterir.

```csharp
[C#]
// PPTX dosyasını bir sunum nesnesine yükler
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // İlk slayta erişir
    ISlide sld = pres.Slides[0];
    // Şekli OleObjectFrame tipine dönüştürür
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // OLE nesnesini okur ve diske yazar
    if (oleObjectFrame != null)
    {
        // Gömülü dosya verisini alır
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // Gömülü dosya uzantısını alır
        string fileExtention = oleObjectFrame.EmbeddedData.EmbeddedFileExtension;
        // Çıkarılan dosyayı kaydetmek için bir yol oluşturur
        string extractedPath = "excelFromOLE_out" + fileExtention;
        // Çıkarılan veriyi kaydeder
        using (FileStream fstr = new FileStream(extractedPath, FileMode.Create, FileAccess.Write))
        {
            fstr.Write(data, 0, data.Length);
        }
    }
}
```

### Ayrıca Bakınız

* sınıf [GraphicalObject](../graphicalobject)
* arayüz [IOleObjectFrame](../ioleobjectframe)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->