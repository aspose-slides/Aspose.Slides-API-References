---
title: PresentationLockingBehavior
second_title: Aspose.Slides pro Java – reference API
description: Reprezentuje chování týkající se zpracování  zdrojového souboru nebo  java.io.InputStream při načítání a práci s instancí .
type: docs
url: /cs/com.aspose.slides/presentationlockingbehavior/
---
**Dědičnost:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PresentationLockingBehavior extends System.Enum
```

Reprezentuje chování týkající se zpracování [IPresentation](../../com.aspose.slides/ipresentation) zdroje (soubor nebo java.io.InputStream) během načítání a práce s instancí [IPresentation](../../com.aspose.slides/ipresentation).

--------------------

> ```
> BlobManagementOptions blobOptions = new BlobManagementOptions();
>  blobOptions.setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setBlobManagementOptions(blobOptions);
>  IPresentation pres = new Presentation("pres.pptx", loadOptions);
> ```

--------------------

Zdroj je parametr předávaný konstruktoru [IPresentation](../../com.aspose.slides/ipresentation). V níže uvedeném příkladu je zdrojem soubor "pres.pptx": Pro tento příklad bude zdroj ("pres.pptx" file) zamčen po dobu životnosti instance [IPresentation](../../com.aspose.slides/ipresentation), tzn. nelze jej měnit ani smazat jiným procesem.
## Pole

| Pole | Popis |
| --- | --- |
| [LoadAndRelease](#LoadAndRelease) | Zdroj bude zamčen pouze po dobu vykonání konstruktoru [IPresentation](../../com.aspose.slides/ipresentation). |
| [KeepLocked](#KeepLocked) | Zdroj bude zamčen po celou dobu existence instance [IPresentation](../../com.aspose.slides/ipresentation), dokud nebude zlikvidován. |
### LoadAndRelease {#LoadAndRelease}
```
public static final int LoadAndRelease
```


Zdroj bude zamčen pouze po dobu vykonání konstruktoru [IPresentation](../../com.aspose.slides/ipresentation).

--------------------

Pokud je ([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) nastaveno na false, všechny BLOBy budou načteny do paměti. Jinak mohou být použity jiné prostředky, například dočasné soubory.

--------------------

Toto chování je pomalejší než [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked) a pokud je možné předat vlastnictví zdroje [IPresentation](../../com.aspose.slides/ipresentation), doporučuje se použít [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked).

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```


Zdroj bude zamčen po celou dobu existence instance [IPresentation](../../com.aspose.slides/ipresentation), dokud nebude zlikvidován.

--------------------

[IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) musí být nastaveno na true pro použití tohoto chování, jinak bude vyvolána výjimka.

--------------------

Toto chování je doporučeno, je rychlejší a spotřebovává méně paměti než [LoadAndRelease](../../com.aspose.slides/presentationlockingbehavior\#LoadAndRelease).