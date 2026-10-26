---
title: NewLineHandling
second_title: Αναφορά API Aspose.Slides για C++
description: Καθορίζει πώς να διαχειρίζεστε τις αλλαγές γραμμής.
type: docs
weight: 690
url: /el/system.xml/newlinehandling/
---
## NewLineHandling enum

Καθορίζει πώς να αντιμετωπίζονται οι αλλαγές γραμμής.

```cpp
enum class NewLineHandling
```

### Values

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Replace | 0 | Οι χαρακτήρες νέας γραμμής αντικαθίστανται ώστε να ταιριάζουν με τον χαρακτήρα που καθορίζεται στην τιμή [XmlWriterSettings::set_NewLineChars](../xmlwritersettings/set_newlinechars/). |
| Entitize | 1 | Οι χαρακτήρες νέας γραμμής ενσωματώνονται. Αυτή η ρύθμιση διατηρεί όλους τους χαρακτήρες όταν η έξοδος διαβάζεται από έναν κανονικοποιητικό [XmlReader](../xmlreader/). |
| None | 2 | Οι χαρακτήρες νέας γραμμής παραμένουν αμετάβλητοι. Η έξοδος είναι η ίδια με την είσοδο. |

## See Also

* Χώρος ονομάτων [System::Xml](../)
* Βιβλιοθήκη [Aspose.Slides](../../)