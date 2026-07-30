---
title: set_RootDirectoryClsid()
second_title: Riferimento API Aspose.Slides per C++
description: Rappresenta il GUID (CLSID) della classe dell'oggetto memorizzato nella voce della directory radice. Può essere utilizzato per l'attivazione COM dell'applicazione del documento. Il valore predefinito è '64818D11-4F9B-11CF-86EA-00AA00B929E8' che corrisponde a 'Microsoft Powerpoint.Slide.8'.
type: docs
weight: 14
url: /it/aspose.slides.export/ipptoptions/set_rootdirectoryclsid/
---
## IPptOptions::set_RootDirectoryClsid(System::Guid) metodo


Rappresenta il GUID (CLSID) della classe dell'oggetto memorizzato nella voce della directory radice. Può essere utilizzato per l'attivazione COM dell'applicazione del documento. Il valore predefinito è '64818D11-4F9B-11CF-86EA-00AA00B929E8' che corrisponde a 'Microsoft Powerpoint.Slide.8'.

```cpp
virtual void Aspose::Slides::Export::IPptOptions::set_RootDirectoryClsid(System::Guid value)=0
```

## Osservazioni



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PptOptions> pptOptions = System::MakeObject<PptOptions>();

pptOptions->set_RootDirectoryClsid(System::Guid(u"64818D10-4F9B-11CF-86EA-00AA00B929E8"));

pres->Save(u"pres.ppt", Aspose::Slides::Export::SaveFormat::Ppt, pptOptions);
```




## Vedi anche

* Classe [Guid](../../../system/guid/)
* Classe [IPptOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)