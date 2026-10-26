---
title: get_RootDirectoryClsid()
second_title: Aspose.Slides for C++ API Αναφορά
description: Αντιπροσωπεύει το GUID (CLSID) της κλάσης αντικειμένου που αποθηκεύεται στην καταχώρηση του ριζικού καταλόγου. Μπορεί να χρησιμοποιηθεί για ενεργοποίηση COM της εφαρμογής του εγγράφου. Η προεπιλεγμένη τιμή είναι '64818D11-4F9B-11CF-86EA-00AA00B929E8' η οποία αντιστοιχεί στο 'Microsoft Powerpoint.Slide.8'.
type: docs
weight: 1
url: /el/aspose.slides.export/pptoptions/get_rootdirectoryclsid/
---
## PptOptions::get_RootDirectoryClsid() μέθοδος


Αντιπροσωπεύει το GUID (CLSID) της κλάσης αντικειμένου που αποθηκεύεται στην καταχώρηση του ριζικού καταλόγου. Μπορεί να χρησιμοποιηθεί για ενεργοποίηση COM της εφαρμογής του εγγράφου. Η προεπιλεγμένη τιμή είναι '64818D11-4F9B-11CF-86EA-00AA00B929E8' η οποία αντιστοιχεί στο 'Microsoft Powerpoint.Slide.8'.

```cpp
System::Guid Aspose::Slides::Export::PptOptions::get_RootDirectoryClsid() override
```

## Παρατηρήσεις



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PptOptions> pptOptions = System::MakeObject<PptOptions>();

pptOptions->set_RootDirectoryClsid(System::Guid(u"64818D10-4F9B-11CF-86EA-00AA00B929E8"));

pres->Save(u"pres.ppt", Aspose::Slides::Export::SaveFormat::Ppt, pptOptions);
```



## Δείτε επίσης

* Κλάση [Guid](../../../system/guid/)
* Κλάση [PptOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)