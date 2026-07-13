---
title: PresentationLockingBehavior
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Reprezentuje zachowanie dotyczące traktowania pliku źródłowego lub java.io.InputStream podczas ładowania i pracy z instancją.
type: docs
url: /pl/com.aspose.slides/presentationlockingbehavior/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PresentationLockingBehavior extends System.Enum
```

Reprezentuje zachowanie dotyczące traktowania źródła [IPresentation](../../com.aspose.slides/ipresentation) (pliku lub java.io.InputStream) podczas ładowania i pracy z instancją [IPresentation](../../com.aspose.slides/ipresentation).

--------------------

> ```
> BlobManagementOptions blobOptions = new BlobManagementOptions();
>  blobOptions.setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setBlobManagementOptions(blobOptions);
>  IPresentation pres = new Presentation("pres.pptx", loadOptions);
> ```

--------------------

Źródło jest parametrem przekazywanym do konstruktora [IPresentation](../../com.aspose.slides/ipresentation). W poniższym przykładzie źródłem jest plik "pres.pptx": Dla tego przykładu źródło ("pres.pptx" file) zostanie zablokowane na cały okres życia instancji [IPresentation](../../com.aspose.slides/ipresentation), tzn. nie może być zmieniane ani usuwane przez inny proces.
## Pola

| Pole | Opis |
| --- | --- |
| [LoadAndRelease](#LoadAndRelease) | Źródło zostanie zablokowane tylko na czas wykonywania konstruktora [IPresentation](../../com.aspose.slides/ipresentation). |
| [KeepLocked](#KeepLocked) | Źródło zostanie zablokowane na cały okres życia instancji [IPresentation](../../com.aspose.slides/ipresentation), aż zostanie zwolnione. |
### LoadAndRelease {#LoadAndRelease}
```
public static final int LoadAndRelease
```

Źródło zostanie zablokowane tylko na czas wykonywania konstruktora [IPresentation](../../com.aspose.slides/ipresentation).

--------------------

Jeśli ([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) jest ustawione na false, wszystkie BLOBy zostaną załadowane do pamięci. W przeciwnym razie mogą zostać użyte inne środki, np. pliki tymczasowe.

--------------------

To zachowanie jest wolniejsze niż [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked), a jeśli możliwe jest przekazanie własności źródła do [IPresentation](../../com.aspose.slides/ipresentation), zaleca się użycie [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked).

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

Źródło zostanie zablokowane na cały okres życia instancji [IPresentation](../../com.aspose.slides/ipresentation), aż zostanie zwolnione.

--------------------

[IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) musi być ustawione na true, aby używać tego zachowania, w przeciwnym razie zostanie rzucony wyjątek.

--------------------

To zachowanie jest zalecane, jest szybsze i zużywa mniej pamięci niż [LoadAndRelease](../../com.aspose.slides/presentationlockingbehavior\#LoadAndRelease).