---
title: License()
second_title: Aspose.Slides für C++ API-Referenz
description: Initialisiert eine neue Instanz dieser Klasse.
type: docs
weight: 1
url: /de/aspose.slides/license/license/
---
## License::License() Konstruktor


Initialisiert eine neue Instanz dieser Klasse.

```cpp
Aspose::Slides::License::License()
```

## Hinweise


In diesem Beispiel wird versucht, eine Lizenzdatei mit dem Namen MyLicense.lic im Ordner zu finden, der die Komponente enthält, im Ordner, der die aufrufende Assembly enthält, im Ordner der Einstieg-Assembly und anschließend in den eingebetteten Ressourcen der aufrufenden Assembly. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## Siehe auch

* Klasse [License](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)