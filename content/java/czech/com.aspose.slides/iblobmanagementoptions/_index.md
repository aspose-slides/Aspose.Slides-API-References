---
title: IBlobManagementOptions
second_title: Aspose.Slides for Java API Reference
description: A Binary Large Object BLOB is a binary data stored as a single entity - i.e.
type: docs
url: /cs/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

Binární velký objekt (BLOB) je binární data uložená jako jedinečná entita – tj. BLOB může být audio, video nebo samotná prezentace. K optimalizaci spotřeby paměti při práci s BLOBy se používá řada technik – které jsou již uloženy v prezentaci nebo mohou být později přidány programově. Pomocí [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) můžete změnit různé aspekty chování týkající se manipulace s BLOBy pro životnost instance [IPresentation](../../com.aspose.slides/ipresentation).

## Metody

| Metoda | Popis |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Tato vlastnost určuje, zda může být instance třídy Presentation vlastníkem zdroje – souboru nebo streamu během životnosti instance. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Tato vlastnost určuje, zda může být instance třídy Presentation vlastníkem zdroje – souboru nebo streamu během životnosti instance. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Tato vlastnost určuje, zda mohou být během práce s BLOBy vytvářeny dočasné soubory, což výrazně snižuje spotřebu paměti, ale vyžaduje oprávnění k vytváření souborů. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Tato vlastnost určuje, zda mohou být během práce s BLOBy vytvářeny dočasné soubory, což výrazně snižuje spotřebu paměti, ale vyžaduje oprávnění k vytváření souborů. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Kořenová cesta, kde budou vytvářeny dočasné soubory. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Kořenová cesta, kde budou vytvářeny dočasné soubory. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Definuje maximální celkovou velikost (v bajtech), kterou mohou všechny BLOBy zabírat v paměti. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Definuje maximální celkovou velikost (v bajtech), kterou mohou všechny BLOBy zabírat v paměti. |

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

Tato vlastnost určuje, zda může být instance třídy Presentation vlastníkem zdroje – souboru nebo streamu během životnosti instance. Pokud je instance vlastníkem, zamyká zdroj. To pomáhá zlepšit spotřebu paměti a výkon při práci s BLOBy, ale zdroj (stream nebo soubor) nelze během životnosti instance Presentation měnit. Toto je příklad:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException bude vyvolána, protože soubor pres.pptx je uzamčen po dobu životnosti Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // po uvolnění objektu Presentation je soubor odemčen a může být smazán
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```

**Vrací:**
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

Tato vlastnost určuje, zda může být instance třídy Presentation vlastníkem zdroje – souboru nebo streamu během životnosti instance. Pokud je instance vlastníkem, zamyká zdroj. To pomáhá zlepšit spotřebu paměti a výkon při práci s BLOBy, ale zdroj (stream nebo soubor) nelze během životnosti instance Presentation měnit. Toto je příklad:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException bude vyvolána, protože soubor pres.pptx je uzamčen po dobu životnosti Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // po uvolnění objektu Presentation je soubor odemčen a může být smazán
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public abstract boolean isTemporaryFilesAllowed()
```

Tato vlastnost určuje, zda mohou být během práce s BLOBy vytvářeny dočasné soubory, což výrazně snižuje spotřebu paměti, ale vyžaduje oprávnění k vytváření souborů.

--------------------

Všechny soubory budou po dokončení práce s prezentací smazány.

**Vrací:**
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
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
public abstract String getTempFilesRootPath()
```

Kořenová cesta, kde budou vytvářeny dočasné soubory. Výchozí bude použita systémová dočasná složka. Hostitelský proces by měl mít oprávnění k vytváření souborů a složek v tomto umístění.

**Vrací:**
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

Kořenová cesta, kde budou vytvářeny dočasné soubory. Výchozí bude použita systémová dočasná složka. Hostitelský proces by měl mít oprávnění k vytváření souborů a složek v tomto umístění.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

Definuje maximální celkovou velikost (v bajtech), kterou mohou všechny BLOBy zabírat v paměti. Ve výchozím nastavení jsou všechny BLOBy načteny do paměti; až po dosažení tohoto limitu jsou použity alternativní mechanismy (například dočasné soubory). Udržování BLOBů v paměti maximalizuje výkon, ale může vést k vysoké spotřebě paměti. Použijte tuto vlastnost k úpravě chování podle svého prostředí nebo požadavků.

--------------------

Tato vlastnost je ignorována, pokud je \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) nastaveno na false, protože paměť je pak jediným dostupným úložištěm a omezení používání BLOBů v paměti nemá žádný efekt.

--------------------

Výchozí hodnota je 629 145 600 bajtů (600 MB).

--------------------

Můžete nastavit tuto vlastnost na nulu, ale malé minimální množství paměti bude i tak rezervováno.

**Vrací:**
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

Definuje maximální celkovou velikost (v bajtech), kterou mohou všechny BLOBy zabírat v paměti. Ve výchozím nastavení jsou všechny BLOBy načteny do paměti; až po dosažení tohoto limitu jsou použity alternativní mechanismy (například dočasné soubory). Udržování BLOBů v paměti maximalizuje výkon, ale může vést k vysoké spotřebě paměti. Použijte tuto vlastnost k úpravě chování podle svého prostředí nebo požadavků.

--------------------

Tato vlastnost je ignorována, pokud je \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) nastaveno na false, protože paměť je pak jediným dostupným úložištěm a omezení používání BLOBů v paměti nemá žádný efekt.

--------------------

Výchozí hodnota je 629 145 600 bajtů (600 MB).

--------------------

Můžete nastavit tuto vlastnost na nulu, ale malé minimální množství paměti bude i tak rezervováno.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |