---
title: BlobManagementOptions
second_title: Aspose.Slides pro Java – referenční příručka API
description: Představuje možnosti, které lze použít ke správě pravidel pro zacházení s BLOBy a dalších nastavení BLOB.
type: docs
url: /cs/com.aspose.slides/blobmanagementoptions/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
```
public class BlobManagementOptions implements IBlobManagementOptions
```

Představuje možnosti, které lze použít ke správě pravidel pro zacházení s BLOBy a dalších nastavení BLOB.

## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | Vytvoří nové výchozí nastavení správy blobů. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Tato vlastnost určuje, zda může instance třídy Presentation být vlastníkem zdroje – souboru nebo proudu během životnosti instance. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Tato vlastnost určuje, zda může instance třídy Presentation být vlastníkem zdroje – souboru nebo proudu během životnosti instance. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Tato vlastnost určuje, zda mohou být během práce s BLOBy vytvářeny dočasné soubory, což výrazně snižuje spotřebu paměti, ale vyžaduje oprávnění k vytváření souborů. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Tato vlastnost určuje, zda mohou být během práce s BLOBy vytvářeny dočasné soubory, což výrazně snižuje spotřebu paměti, ale vyžaduje oprávnění k vytváření souborů. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Kořenová cesta, kde budou vytvářeny dočasné soubory. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Kořenová cesta, kde budou vytvářeny dočasné soubory. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Definuje maximální celkovou velikost (v bajtech), kterou mohou všechny BLOBy zabírat v paměti. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Definuje maximální celkovou velikost (v bajtech), kterou mohou všechny BLOBy zabírat v paměti. |
### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```


Vytvoří nové výchozí nastavení správy blobů.

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```


Tato vlastnost určuje, zda může instance třídy Presentation být vlastníkem zdroje – souboru nebo proudu během životnosti instance. Pokud je instance vlastníkem, uzamkne zdroj. To pomáhá zlepšit spotřebu paměti a výkon při práci s BLOBy, ale zdroj (proud nebo soubor) nelze během životnosti instance Presentation měnit.

**Vrací:**
int
### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```


Tato vlastnost určuje, zda může instance třídy Presentation být vlastníkem zdroje – souboru nebo proudu během životnosti instance. Pokud je instance vlastníkem, uzamkne zdroj. To pomáhá zlepšit spotřebu paměti a výkon při práci s BLOBy, ale zdroj (proud nebo soubor) nelze během životnosti instance Presentation měnit.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```


Tato vlastnost určuje, zda mohou být během práce s BLOBy vytvářeny dočasné soubory, což výrazně snižuje spotřebu paměti, ale vyžaduje oprávnění k vytváření souborů.

--------------------

Všechny soubory budou po dokončení práce s prezentací smazány.

**Vrací:**
boolean
### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```


Tato vlastnost určuje, zda mohou být během práce s BLOBy vytvářeny dočasné soubory, což výrazně snižuje spotřebu paměti, ale vyžaduje oprávnění k vytváření souborů.

--------------------

Všechny soubory budou po dokončení práce s prezentací smazány.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public final String getTempFilesRootPath()
```


Kořenová cesta, kde budou vytvářeny dočasné soubory. Ve výchozím nastavení bude použita systémová dočasná složka. Hostitelský proces by měl mít oprávnění k vytváření souborů a složek v tomto umístění.

**Vrací:**
java.lang.String
### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```


Kořenová cesta, kde budou vytvářeny dočasné soubory. Ve výchozím nastavení bude použita systémová dočasná složka. Hostitelský proces by měl mít oprávnění k vytváření souborů a složek v tomto umístění.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```


Definuje maximální celkovou velikost (v bajtech), kterou mohou všechny BLOBy zabírat v paměti. Ve výchozím nastavení jsou všechny BLOBy načteny do paměti; jen po dosažení tohoto limitu jsou použity alternativní mechanismy (například dočasné soubory). Udržování BLOBů v paměti maximalizuje výkon, ale může vést k vysoké spotřebě paměti. Použijte tuto vlastnost k přizpůsobení chování vašemu prostředí nebo požadavkům.

--------------------

Tato vlastnost je ignorována, pokud \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) je nastaveno na false, protože v tom případě je paměť jediným možným úložištěm a omezení využití BLOBů v paměti nemá žádný efekt.

--------------------

Výchozí hodnota je 629 145 600 bajtů (600 MB).

--------------------

Můžete tuto vlastnost nastavit na nulu, ale malé minimální množství paměti bude stále rezervováno.

**Vrací:**
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```


Definuje maximální celkovou velikost (v bajtech), kterou mohou všechny BLOBy zabírat v paměti. Ve výchozím nastavení jsou všechny BLOBy načteny do paměti; jen po dosažení tohoto limitu jsou použity alternativní mechanismy (například dočasné soubory). Udržování BLOBů v paměti maximalizuje výkon, ale může vést k vysoké spotřebě paměti. Použijte tuto vlastnost k přizpůsobení chování vašemu prostředí nebo požadavkům.

--------------------

Tato vlastnost je ignorována, pokud \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) je nastaveno na false, protože v tom případě je paměť jediným možným úložištěm a omezení využití BLOBů v paměti nemá žádný efekt.

--------------------

Výchozí hodnota je 629 145 600 bajtů (600 MB).

--------------------

Můžete tuto vlastnost nastavit na nulu, ale malé minimální množství paměti bude stále rezervováno.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |