---
title: set_license method
second_title: Aspose.Slides pro Python přes .NET referenční příručka API
description: 
type: docs
url: /cs/aspose.slides/license/set_license/
weight: 40
---
## set_license(self, license_name) {#str}
Licencuje komponentu.

```python
def set_license(self, license_name):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| license_name | **str** | Může být úplný nebo zkrácený název souboru nebo název vloženého zdroje.<br/><br/>            Použijte prázdný řetězec pro přepnutí do režimu hodnocení. |

### Poznámky

Pokusí se najít licenci v následujících umístěních:

1. Explicitní cesta.

2. Složka sestavení komponenty.

3. Složka sestavení volajícího klienta.

4. Složka vstupního sestavení.

5. Vložený zdroj ve volajícím sestavení klienta.

**Poznámka:** V .NET Compact Framework se pokusí najít licenci pouze v těchto umístěních:

1. Explicitní cesta.

2. Vložený zdroj ve volajícím sestavení klienta.

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
* třída [`License`](/slides/python-net/cs/aspose.slides/license)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)