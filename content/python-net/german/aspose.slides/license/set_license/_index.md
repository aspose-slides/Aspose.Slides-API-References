---
title: set_license method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/license/set_license/
weight: 40
---
## set_license(self, license_name) {#str}
Lizenziert die Komponente.


```python
def set_license(self, license_name):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| license_name | **str** | Kann ein vollständiger oder kurzer Dateiname oder der Name einer eingebetteten Ressource sein.<br/><br/>            Verwenden Sie eine leere Zeichenkette, um in den Evaluierungsmodus zu wechseln. |

### Hinweise

Versucht, die Lizenz an den folgenden Orten zu finden:


1. Expliziter Pfad.

2. Der Ordner der Komponenten-Assembly.

3. Der Ordner der aufrufenden Assembly des Clients.

4. Der Ordner der Entry-Assembly.

5. Eine eingebettete Ressource in der aufrufenden Assembly des Clients.

**Hinweis:** Unter dem .NET Compact Framework wird versucht, die Lizenz nur an diesen Speicherorten zu finden:


1. Expliziter Pfad.

2. Eine eingebettete Ressource in der aufrufenden Assembly des Clients.


## set_license(self, stream) {#iorawiobase}
Lizenziert die Komponente.


```python
def set_license(self, stream):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | **io.RawIOBase** | Ein Stream, der die Lizenz enthält. |

### Hinweise

Verwenden Sie diese Methode, um eine Lizenz aus einem Stream zu laden.



### Siehe auch
* Klasse [`License`](/slides/python-net/de/aspose.slides/license)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)