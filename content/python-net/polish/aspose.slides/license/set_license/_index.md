---
title: set_license method
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET API Reference
description: 
type: docs
url: /pl/aspose.slides/license/set_license/
weight: 40
---
## set_license(self, license_name) {#str}
Licencjonuje komponent.

```python
def set_license(self, license_name):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| license_name | **str** | Może być pełną lub krótką nazwą pliku lub nazwą osadzonego zasobu.<br/><br/>            Użyj pustego łańcucha, aby przełączyć w tryb ewaluacji. |

### Uwagi

Próbuje znaleźć licencję w następujących lokalizacjach:

1. Ścieżka jawna.

2. Folder zestawu komponentu.

3. Folder wywołującego zestawu klienta.

4. Folder zestawu wejściowego.

5. Osadzony zasób w wywołującym zestawie klienta.

**Uwaga:** Na platformie .NET Compact Framework próbuje znaleźć licencję tylko w tych lokalizacjach:

1. Ścieżka jawna.

2. Osadzony zasób w wywołującym zestawie klienta.

## set_license(self, stream) {#iorawiobase}
Licencjonuje komponent.

```python
def set_license(self, stream):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Strumień zawierający licencję. |

### Uwagi

Użyj tej metody, aby wczytać licencję ze strumienia.

### Zobacz też
* klasa [`License`](/slides/python-net/pl/aspose.slides/license)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)