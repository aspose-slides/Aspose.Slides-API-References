---
title: set_RootDirectoryClsid()
second_title: Referencia API de Aspose.Slides para C++
description: Representa el GUID de la clase de objeto (CLSID) que se almacena en la entrada del directorio raíz. Puede usarse para la activación COM de la aplicación del documento. El valor predeterminado es '64818D11-4F9B-11CF-86EA-00AA00B929E8', que corresponde a 'Microsoft Powerpoint.Slide.8'.
type: docs
weight: 14
url: /es/aspose.slides.export/ipptoptions/set_rootdirectoryclsid/
---
## IPptOptions::set_RootDirectoryClsid(System::Guid) método


Representa el GUID de la clase de objeto (CLSID) que se almacena en la entrada del directorio raíz. Puede usarse para la activación COM de la aplicación del documento. El valor predeterminado es '64818D11-4F9B-11CF-86EA-00AA00B929E8', que corresponde a 'Microsoft Powerpoint.Slide.8'.

```cpp
virtual void Aspose::Slides::Export::IPptOptions::set_RootDirectoryClsid(System::Guid value)=0
```

## Observaciones



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PptOptions> pptOptions = System::MakeObject<PptOptions>();

pptOptions->set_RootDirectoryClsid(System::Guid(u"64818D10-4F9B-11CF-86EA-00AA00B929E8"));

pres->Save(u"pres.ppt", Aspose::Slides::Export::SaveFormat::Ppt, pptOptions);
```




## Véase también

* Clase [Guid](../../../system/guid/)
* Clase [IPptOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)