---
title: get_RootDirectoryClsid()
second_title: Aspose.Slides para C++ Referência da API
description: Representa o GUID (CLSID) da classe de objeto que é armazenado na entrada do diretório raiz. Pode ser usado para a ativação COM da aplicação do documento. O valor padrão é '64818D11-4F9B-11CF-86EA-00AA00B929E8' que corresponde a 'Microsoft Powerpoint.Slide.8'.
type: docs
weight: 1
url: /pt/aspose.slides.export/pptoptions/get_rootdirectoryclsid/
---
## PptOptions::get_RootDirectoryClsid() method


Representa o GUID (CLSID) da classe de objeto que é armazenado na entrada do diretório raiz. Pode ser usado para a ativação COM da aplicação do documento. O valor padrão é '64818D11-4F9B-11CF-86EA-00AA00B929E8' que corresponde a 'Microsoft Powerpoint.Slide.8'.

```cpp
System::Guid Aspose::Slides::Export::PptOptions::get_RootDirectoryClsid() override
```

## Observações



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PptOptions> pptOptions = System::MakeObject<PptOptions>();

pptOptions->set_RootDirectoryClsid(System::Guid(u"64818D10-4F9B-11CF-86EA-00AA00B929E8"));

pres->Save(u"pres.ppt", Aspose::Slides::Export::SaveFormat::Ppt, pptOptions);
```




## Veja Também

* Classe [Guid](../../../system/guid/)
* Classe [PptOptions](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)