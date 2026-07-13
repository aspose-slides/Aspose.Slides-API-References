---
title: BlobManagementOptions
second_title: Aspose.Slides pro Android – referenční příručka Java API
description: Reprezentuje možnosti, které lze použít ke správě pravidel zpracování BLOB a dalších nastavení BLOB.
type: docs
url: /cs/com.aspose.slides/blobmanagementoptions/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)  
```
public class BlobManagementOptions implements IBlobManagementOptions
```

Reprezentuje možnosti, které lze použít ke správě pravidel zpracování BLOB a dalších nastavení BLOB.

## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | Vytvoří nové výchozí možnosti správy BLOB. |

## Metody

| Metoda | Popis |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Tato vlastnost určuje, zda může instance třídy Presentation být vlastníkem zdroje – souboru nebo proudu během životnosti instance. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Tato vlastnost určuje, zda může instance třídy Presentation být vlastníkem zdroje – souboru nebo proudu během životnosti instance. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Tato vlastnost určuje, zda mohou být během práce s BLOBy vytvářeny dočasné soubory, což výrazně snižuje spotřebu paměti, ale vyžaduje oprávnění k vytváření souborů. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Tato vlastnost určuje, zda mohou být během práce s BLOBy vytvářeny dočasné soubory, což výrazně snižuje spotřebu paměti, ale vyžaduje oprávnění k vytváření souborů. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Kořenová cesta, kde budou vytvořeny dočasné soubory. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Kořenová cesta, kde budou vytvořeny dočasné soubory. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Definuje maximální celkovou velikost (v bajtech), kterou mohou všechny BLOBy zabírat v paměti. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Definuje maximální celkovou velikost (v bajtech), kterou mohou všechny BLOBy zabírat v paměti. |

### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```

Vytvoří nové výchozí možnosti správy BLOB.

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```

Tato vlastnost určuje, zda může instance třídy Presentation být vlastníkem zdroje – souboru nebo proudu během životnosti instance. Pokud je instance vlastníkem, zamkne zdroj. To pomáhá zlepšit spotřebu paměti a výkon při práci s BLOBy, ale zdroj (proud nebo soubor) nelze během životnosti instance Presentation měnit.

**Vrací:**  
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```

Tato vlastnost určuje, zda může instance třídy Presentation být vlastníkem zdroje – souboru nebo proudu během životnosti instance. Pokud je instance vlastníkem, zamkne zdroj. To pomáhá zlepšit spotřebu paměti a výkon při práci s BLOBy, ale zdroj (proud nebo soubor) nelze během životnosti instance Presentation měnit.

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

Kořenová cesta, kde budou vytvořeny dočasné soubory. Ve výchozím nastavení bude použita systémová dočasná složka. Hostitelský proces by zde měl mít oprávnění vytvářet soubory a složky.

**Vrací:**  
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```

Kořenová cesta, kde budou vytvořeny dočasné soubory. Ve výchozím nastavení bude použita systémová dočasná složka. Hostitelský proces by zde měl mít oprávnění vytvářet soubory a složky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```

Definuje maximální celkovou velikost (v bajtech), kterou mohou všechny BLOBy zabírat v paměti. Ve výchozím nastavení jsou všechny BLOBy načteny do paměti; až po dosažení tohoto limitu jsou použity alternativní mechanismy (např. dočasné soubory). Uchovávání BLOBů v paměti maximalizuje výkon, ale může vést k vysokému využití paměti. Použijte tuto vlastnost k přizpůsobení chování vašemu prostředí nebo požadavkům.

--------------------

Tato vlastnost je ignorována, pokud je \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) nastavena na false, protože paměť je pak jediným dostupným úložištěm a omezení používání BLOBů v paměti nemá žádný efekt.

--------------------

Výchozí hodnota je 629 145 600 bajtů (600 MB).

--------------------

Můžete nastavit tuto vlastnost na nulu, ale malé minimální množství paměti bude i přesto rezervováno.

**Vrací:**  
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```

Definuje maximální celkovou velikost (v bajtech), kterou mohou všechny BLOBy zabírat v paměti. Ve výchozím nastavení jsou všechny BLOBy načteny do paměti; až po dosažení tohoto limitu jsou použity alternativní mechanismy (např. dočasné soubory). Uchovávání BLOBů v paměti maximalizuje výkon, ale může vést k vysokému využití paměti. Použijte tuto vlastnost k přizpůsobení chování vašemu prostředí nebo požadavkům.

--------------------

Tato vlastnost je ignorována, pokud je \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) nastavena na false, protože paměť je pak jediným dostupným úložištěm a omezení používání BLOBů v paměti nemá žádný efekt.

--------------------

Výchozí hodnota je 629 145 600 bajtů (600 MB).

--------------------

Můžete nastavit tuto vlastnost na nulu, ale malé minimální množství paměti bude i přesto rezervováno.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |