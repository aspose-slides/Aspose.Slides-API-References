---
title: AddOleObjectFrame()
second_title: Aspose.Slides for C++ API Referansı
description: Yeni bir OLE nesne çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.
type: docs
weight: 183
url: /tr/aspose.slides/shapecollection/addoleobjectframe/
---
## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) method

Yeni bir OLE nesne çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | **float** | Yeni OLE çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni OLE çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni OLE çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni OLE çerçevesinin yüksekliği, puan cinsinden. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Gömülü OLE verileri hakkında bilgi ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Dönüş Değeri

Yeni oluşturulan [IOleObjectFrame](../../ioleobjectframe/).

## Açıklamalar

Aşağıdaki örnekler, PowerPoint [Presentation](../../presentation/)'nin [Slides](../../)'ne OLE Nesne Çerçevelerinin nasıl ekleneceğini gösterir. 
```cpp
auto pres = System::MakeObject<Presentation>();

// İlk slayta erişir
auto slide = pres->get_Slides()->idx_get(0);
// Excel dosyasını akıma yükler
System::SharedPtr<System::IO::MemoryStream> mstream = System::MakeObject<System::IO::MemoryStream>();
auto fs = System::MakeObject<System::IO::FileStream>(u"book1.xlsx", System::IO::FileMode::Open, System::IO::FileAccess::Read);

System::ArrayPtr<uint8_t> buf = System::MakeArray<uint8_t>(4096, 0);
while (true)
{
    int32_t bytesRead = fs->Read(buf, 0, buf->get_Length());
    if (bytesRead <= 0)
    {
        break;
    }
    mstream->Write(buf, 0, bytesRead);
}

// Gömme için bir veri nesnesi oluşturur
auto dataInfo = System::MakeObject<OleEmbeddedDataInfo>(mstream->ToArray(), u"xlsx");
// Bir Ole Nesne Çerçevesi şekli ekler
auto slideSize = pres->get_SlideSize()->get_Size();
auto oleObjectFrame = slide->get_Shapes()->AddOleObjectFrame(0.0f, 0.0f, slideSize.get_Width(), slideSize.get_Height(), dataInfo);
// PPTX dosyasını diske yazar
pres->Save(u"OleEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) method

Yeni bir OLE nesne çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | **float** | Yeni OLE çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni OLE çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni OLE çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni OLE çerçevesinin yüksekliği, puan cinsinden. |
| className | [System::String](../../../system/string/) | OLE nesnesinin sınıf adı. |
| path | [System::String](../../../system/string/) | Bağlantılı dosyanın yolu. |

### Dönüş Değeri

Yeni oluşturulan [IOleObjectFrame](../../ioleobjectframe/).

## Açıklamalar

Bu yol, sunumda olduğu gibi saklanır. Göreceli bir yol belirtilirse, sunum farklı bir dizinden açıldığında dosyaya erişilemez.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IOleObjectFrame](../../ioleobjectframe/)
* Sınıf [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Sınıf [ShapeCollection](../)
* Sınıf [String](../../../system/string/)
* Ad alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)