---
title: set_license method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/ilicense/set_license/
weight: 30
---
## set_license(self, license_name) {#str}
Licencuje komponentu.


```python
def set_license(self, license_name):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| license_name | **str** | Může být úplný nebo zkrácený název souboru nebo název vloženého prostředku.<br/><br/>            Použijte prázdný řetězec pro přepnutí do evaluačního režimu. |

### Poznámky

Snaží se najít licenci v následujících umístěních:


1. Explicitní cesta.

2. Složka sestavení komponenty.

3. Složka volající sestavy klienta.

4. Složka vstupní sestavy.

5. Vložený prostředek ve volající sestavě klienta.

**Poznámka:** Na .NET Compact Framework se licence hledá pouze v těchto umístěních:


1. Explicitní cesta.

2. Vložený prostředek ve volající sestavě klienta.


## set_license(self, stream) {#iorawiobase}
Licencuje komponentu.


```python
def set_license(self, stream):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Datový proud, který obsahuje licenci. |

### Poznámky

Použijte tuto metodu k načtení licence z proudu.



### Viz také
* třída [`ILicense`](/slides/python-net/cs/aspose.slides/ilicense)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)