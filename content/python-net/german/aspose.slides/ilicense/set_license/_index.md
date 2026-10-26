---
title: set_license method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ilicense/set_license/
weight: 30
---
## set_license(self, license_name) {#str}
Lizenziert die Komponente.


```python
def set_license(self, license_name):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| license_name | **str** | Kann ein vollständiger oder kurzer Dateiname oder der Name einer eingebetteten Ressource sein.<br/><br/>Verwenden Sie eine leere Zeichenkette, um in den Evaluierungsmodus zu wechseln. |

### Hinweise

Versucht, die Lizenz an den folgenden Stellen zu finden:


1. Expliziter Pfad.

2. Der Ordner der Komponentenassembly.

3. Der Ordner der aufrufenden Assembly des Clients.

4. Der Ordner der Eintrittsassembly.

5. Eine eingebettete Ressource in der aufrufenden Assembly des Clients.

**Hinweis:** Unter .NET Compact Framework versucht, die Lizenz nur an diesen Stellen zu finden:


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
* Klasse [`ILicense`](/slides/python-net/de/aspose.slides/ilicense)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)