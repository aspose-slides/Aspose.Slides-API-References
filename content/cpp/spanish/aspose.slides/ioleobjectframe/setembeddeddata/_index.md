---
title: SetEmbeddedData()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece información sobre los datos incrustados de OLE.
type: docs
weight: 248
url: /es/aspose.slides/ioleobjectframe/setembeddeddata/
---
## IOleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) método

Establece información sobre los datos incrustados de OLE.

```cpp
virtual void Aspose::Slides::IOleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Datos incrustados [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |

## Observaciones

Este método cambia las propiedades del objeto para reflejar los nuevos datos y establece la bandera IsObjectLink en false, indicando que el objeto OLE está incrustado.

El siguiente ejemplo muestra cómo cambiar los datos incrustados de OLE y su tipo para un objeto [IOleObjectFrame](../) existente 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<OleObjectFrame> oof = System::AsCast<Aspose::Slides::OleObjectFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
if (oof != nullptr)
{
    System::SharedPtr<IOleEmbeddedDataInfo> newData = System::MakeObject<OleEmbeddedDataInfo>(System::IO::File::ReadAllBytes(u"Picture.png"), u"png");
    oof->SetEmbeddedData(newData);
}
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Clase [IOleObjectFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)