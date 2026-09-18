---
title: set_license method
second_title: Aspose.Slides dla Pythona w .NET – referencja API
description: 
type: docs
url: /pl/aspose.slides/ilicense/set_license/
weight: 30
---
## set_license(self, license_name) {#str}
Licencjonuje komponent.


```python
def set_license(self, license_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| license_name | **str** | Może być pełną lub krótką nazwą pliku lub nazwą osadzonego zasobu.<br/><br/>Użyj pustego łańcucha, aby przełączyć w tryb ewaluacji. |

### Uwagi

Próbuje znaleźć licencję w następujących miejscach:


1. Ścieżka jawna.

2. Folder zestawu komponentu.

3. Folder zestawu wywołującego klienta.

4. Folder zestawu wejściowego.

5. Osadzony zasób w zestawie wywołującym klienta.

**Uwaga:** W .NET Compact Framework próbuje znaleźć licencję tylko w tych miejscach:


1. Ścieżka jawna.

2. Osadzony zasób w zestawie wywołującym klienta.


## set_license(self, stream) {#iorawiobase}
Licencjonuje komponent.


```python
def set_license(self, stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Strumień zawierający licencję. |

### Uwagi

Użyj tej metody, aby wczytać licencję ze strumienia.



### Zobacz także
* klasa [`ILicense`](/slides/python-net/pl/aspose.slides/ilicense)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)