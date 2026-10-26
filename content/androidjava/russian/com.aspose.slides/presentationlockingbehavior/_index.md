---
title: PresentationLockingBehavior
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет поведение, связанное с обработкой исходного файла или java.io.InputStream при загрузке и работе с экземпляром.
type: docs
url: /ru/com.aspose.slides/presentationlockingbehavior/
---
**Наследование:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PresentationLockingBehavior extends System.Enum
```

Представляет поведение, касающееся обработки [IPresentation](../../com.aspose.slides/ipresentation) источника (файл или java.io.InputStream) при загрузке и работе с экземпляром [IPresentation](../../com.aspose.slides/ipresentation).

--------------------

> ```
> BlobManagementOptions blobOptions = new BlobManagementOptions();
>  blobOptions.setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setBlobManagementOptions(blobOptions);
>  IPresentation pres = new Presentation("pres.pptx", loadOptions);
> ```


--------------------

Источник — параметр, передаваемый конструктору [IPresentation](../../com.aspose.slides/ipresentation). В приведённом ниже примере источником является файл "pres.pptx": Для этого примера источник ("pres.pptx" файл) будет заблокирован на весь срок жизни экземпляра [IPresentation](../../com.aspose.slides/ipresentation), т.е. его нельзя будет изменить или удалить другим процессом.
## Поля

| Поле | Описание |
| --- | --- |
| [LoadAndRelease](#LoadAndRelease) | Источник будет заблокирован только на время выполнения конструктора [IPresentation](../../com.aspose.slides/ipresentation). |
| [KeepLocked](#KeepLocked) | Источник будет заблокирован на весь срок жизни экземпляра [IPresentation](../../com.aspose.slides/ipresentation), пока он не будет освобождён. |
### LoadAndRelease {#LoadAndRelease}
```
public static final int LoadAndRelease
```


Источник будет заблокирован только на время выполнения конструктора [IPresentation](../../com.aspose.slides/ipresentation).

--------------------

Если ([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) установлено в false, все BLOB будут загружены в память. В противном случае могут использоваться другие средства, например временные файлы.

--------------------

Это поведение медленнее, чем [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked), и если возможно передать владение источником [IPresentation](../../com.aspose.slides/ipresentation), рекомендуется использовать [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked).

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```


Источник будет заблокирован на весь срок жизни экземпляра [IPresentation](../../com.aspose.slides/ipresentation), пока он не будет освобождён.

--------------------

[IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) должно быть установлено в true для использования этого поведения, в противном случае будет выброшено исключение.

--------------------

Это поведение рекомендуется, оно быстрее и потребляет меньше памяти, чем [LoadAndRelease](../../com.aspose.slides/presentationlockingbehavior\#LoadAndRelease).