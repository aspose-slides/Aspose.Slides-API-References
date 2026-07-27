---
title: set_RootDirectoryClsid()
second_title: Referência da API Aspose.Slides para C++
description: Representa o GUID da classe de objeto (CLSID) que é armazenado na entrada do diretório raiz. Pode ser usado para ativação COM da aplicação do documento. O valor padrão é '64818D11-4F9B-11CF-86EA-00AA00B929E8' que corresponde a 'Microsoft Powerpoint.Slide.8'.
type: docs
weight: 14
url: /pt/aspose.slides.export/ipptoptions/set_rootdirectoryclsid/
---
## IPptOptions::set_RootDirectoryClsid(System::Guid) método

Representa o GUID da classe de objeto (CLSID) que é armazenado na entrada do diretório raiz. Pode ser usado para ativação COM da aplicação do documento. O valor padrão é '64818D11-4F9B-11CF-86EA-00AA00B929E8' que corresponde a 'Microsoft Powerpoint.Slide.8'.

```cpp
virtual void Aspose::Slides::Export::IPptOptions::set_RootDirectoryClsid(System::Guid value)=0
```

## Observações



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PptOptions> pptOptions = System::MakeObject<PptOptions>();

pptOptions->set_RootDirectoryClsid(System::Guid(u"64818D10-4F9B-11CF-86EA-00AA00B929E8"));

pres->Save(u"pres.ppt", Aspose::Slides::Export::SaveFormat::Ppt, pptOptions);
```

## Ver também

* Classe [Guid](../../../system/guid/)
* Classe [IPptOptions](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)