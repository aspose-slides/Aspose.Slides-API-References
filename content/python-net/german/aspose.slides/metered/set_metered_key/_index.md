---
title: set_metered_key method
second_title: Aspose.Slides für Python über .NET API Referenz
description: 
type: docs
url: /de/aspose.slides/metered/set_metered_key/
weight: 60
---
## set_metered_key(self, public_key, private_key) {#str-str}
Legt den gemessenen öffentlichen und privaten Schlüssel fest.
Wenn Sie eine gemessene Lizenz erwerben, sollte diese API beim Start der Anwendung aufgerufen werden; normalerweise ist das ausreichend.
Falls jedoch das Hochladen der Verbrauchsdaten ständig fehlschlägt und 24 Stunden überschreitet, wird die Lizenz auf Evaluierungsstatus gesetzt.
Um einen solchen Fall zu vermeiden, sollten Sie den Lizenzstatus regelmäßig prüfen; ist er im Evaluierungsstatus, rufen Sie diese API erneut auf.

```python
def set_metered_key(self, public_key, private_key):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| public_key | **str** | öffentlicher Schlüssel |
| private_key | **str** | privater Schlüssel |

### Siehe auch
* Klasse [`Metered`](/slides/python-net/de/aspose.slides/metered)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)