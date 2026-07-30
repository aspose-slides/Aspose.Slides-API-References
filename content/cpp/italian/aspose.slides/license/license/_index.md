---
title: License()
second_title: Riferimento API di Aspose.Slides per C++
description: Inizializza una nuova istanza di questa classe.
type: docs
weight: 1
url: /it/aspose.slides/license/license/
---
## License::License() costruttore


Inizializza una nuova istanza di questa classe.

```cpp
Aspose::Slides::License::License()
```

## Osservazioni


In questo esempio, si proverà a trovare un file di licenza denominato MyLicense.lic nella cartella che contiene il componente, nella cartella che contiene l'assembly chiamante, nella cartella dell'assembly di ingresso e quindi nelle risorse incorporate dell'assembly chiamante. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## Vedi anche

* Classe [License](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)