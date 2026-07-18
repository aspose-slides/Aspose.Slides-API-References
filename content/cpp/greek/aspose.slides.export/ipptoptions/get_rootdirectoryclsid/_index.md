---
title: get_RootDirectoryClsid()
second_title: Αναφορά API Aspose.Slides για C++
description: Αναπαριστά το GUID (CLSID) της κλάσης αντικειμένου που αποθηκεύεται στην καταχώρηση του ριζικού καταλόγου. Μπορεί να χρησιμοποιηθεί για ενεργοποίηση COM της εφαρμογής του εγγράφου. Η προεπιλεγμένη τιμή είναι '64818D11-4F9B-11CF-86EA-00AA00B929E8' η οποία αντιστοιχεί στο 'Microsoft Powerpoint.Slide.8'.
type: docs
weight: 1
url: /el/aspose.slides.export/ipptoptions/get_rootdirectoryclsid/
---
## IPptOptions::get_RootDirectoryClsid() μέθοδος


Αναπαριστά το GUID (CLSID) της κλάσης αντικειμένου που αποθηκεύεται στην καταχώρηση του ριζικού καταλόγου. Μπορεί να χρησιμοποιηθεί για ενεργοποίηση COM της εφαρμογής του εγγράφου. Η προεπιλεγμένη τιμή είναι '64818D11-4F9B-11CF-86EA-00AA00B929E8' η οποία αντιστοιχεί στο 'Microsoft Powerpoint.Slide.8'.

```cpp
virtual System::Guid Aspose::Slides::Export::IPptOptions::get_RootDirectoryClsid()=0
```

## Σχόλια



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PptOptions> pptOptions = System::MakeObject<PptOptions>();

pptOptions->set_RootDirectoryClsid(System::Guid(u"64818D10-4F9B-11CF-86EA-00AA00B929E8"));

pres->Save(u"pres.ppt", Aspose::Slides::Export::SaveFormat::Ppt, pptOptions);
```




## Δείτε επίσης

* Κλάση [Guid](../../../system/guid/)
* Κλάση [IPptOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)