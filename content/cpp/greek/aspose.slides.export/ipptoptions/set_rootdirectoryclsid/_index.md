---
title: set_RootDirectoryClsid()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αναπαριστά το GUID (CLSID) της κλάσης αντικειμένου που αποθηκεύεται στην καταχώριση ριζικού καταλόγου. Μπορεί να χρησιμοποιηθεί για ενεργοποίηση COM της εφαρμογής του εγγράφου. Η προεπιλεγμένη τιμή είναι '64818D11-4F9B-11CF-86EA-00AA00B929E8' που αντιστοιχεί στο 'Microsoft Powerpoint.Slide.8'.
type: docs
weight: 14
url: /el/aspose.slides.export/ipptoptions/set_rootdirectoryclsid/
---
## IPptOptions::set_RootDirectoryClsid(System::Guid) μέθοδος

Αναπαριστά το GUID (CLSID) της κλάσης αντικειμένου που αποθηκεύεται στην καταχώριση ριζικού καταλόγου. Μπορεί να χρησιμοποιηθεί για ενεργοποίηση COM της εφαρμογής του εγγράφου. Η προεπιλεγμένη τιμή είναι '64818D11-4F9B-11CF-86EA-00AA00B929E8' που αντιστοιχεί στο 'Microsoft Powerpoint.Slide.8'.

```cpp
virtual void Aspose::Slides::Export::IPptOptions::set_RootDirectoryClsid(System::Guid value)=0
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
* Κλάση [IPptOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)