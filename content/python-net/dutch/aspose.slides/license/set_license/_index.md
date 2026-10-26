---
title: set_license method
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides/license/set_license/
weight: 40
---
## set_license(self, license_name) {#str}
Licenties het component.

```python
def set_license(self, license_name):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| license_name | **str** | Kan een volledige of korte bestandsnaam of de naam van een ingebedde resource zijn.<br/><br/>Gebruik een lege tekenreeks om over te schakelen naar evaluatiemodus. |

### Opmerkingen

Probeert de licentie te vinden op de volgende locaties:

1. Expliciet pad.

2. De map van de componentassembly.

3. De map van de aanroepende assembly van de client.

4. De map van de entry-assembly.

5. Een ingebedde resource in de aanroepende assembly van de client.

**Opmerking:** Op het .NET Compact Framework wordt de licentie alleen gezocht op deze locaties:

1. Expliciet pad.

2. Een ingebedde resource in de aanroepende assembly van de client.

## set_license(self, stream) {#iorawiobase}
Licenties het component.

```python
def set_license(self, stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | **io.RawIOBase** | Een stream die de licentie bevat. |

### Opmerkingen

Gebruik deze methode om een licentie uit een stream te laden.

### Zie ook
* klasse [`License`](/slides/python-net/nl/aspose.slides/license)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)