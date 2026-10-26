---
title: PresentationLockingBehavior
second_title: Aspose.Slides für Android über die Java API-Referenz
description: Stellt das Verhalten hinsichtlich der Behandlung der Quelldatei oder java.io.InputStream beim Laden und Arbeiten mit einer Instanz von dar.
type: docs
url: /de/com.aspose.slides/presentationlockingbehavior/
---
**Vererbung:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PresentationLockingBehavior extends System.Enum
```

Stellt das Verhalten bezüglich der Behandlung der [IPresentation](../../com.aspose.slides/ipresentation) Quelle (Datei oder java.io.InputStream) beim Laden und Arbeiten mit einer Instanz von [IPresentation](../../com.aspose.slides/ipresentation) dar.

--------------------

> ```
> BlobManagementOptions blobOptions = new BlobManagementOptions();
>  blobOptions.setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setBlobManagementOptions(blobOptions);
>  IPresentation pres = new Presentation("pres.pptx", loadOptions);
> ```

--------------------

Die Quelle ist der Parameter, der dem [IPresentation](../../com.aspose.slides/ipresentation) Konstruktor übergeben wird. Im nachfolgenden Beispiel ist die Quelle die Datei "pres.pptx": Für dieses Beispiel wird die Quelle ("pres.pptx"-Datei) für die Lebensdauer einer [IPresentation](../../com.aspose.slides/ipresentation) Instanz gesperrt, d. h. sie kann von einem anderen Prozess nicht geändert oder gelöscht werden.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [LoadAndRelease](#LoadAndRelease) | Die Quelle wird nur für die Dauer der Ausführung des [IPresentation](../../com.aspose.slides/ipresentation) Konstruktors gesperrt. |
| [KeepLocked](#KeepLocked) | Die Quelle wird für die gesamte Lebensdauer einer [IPresentation](../../com.aspose.slides/ipresentation) Instanz gesperrt, bis sie entsorgt wird. |
### LoadAndRelease {#LoadAndRelease}
```
public static final int LoadAndRelease
```


Die Quelle wird nur für die Dauer der Ausführung des [IPresentation](../../com.aspose.slides/ipresentation) Konstruktors gesperrt.

--------------------

Wenn ([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) auf false gesetzt ist, werden alle BLOBs in den Speicher geladen. Andernfalls können andere Mittel wie temporäre Dateien verwendet werden.

--------------------

Dieses Verhalten ist langsamer als [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked), und wenn es möglich ist, den Besitz der Quelle an [IPresentation](../../com.aspose.slides/ipresentation) zu übergeben, wird empfohlen, [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked) zu verwenden.

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```


Die Quelle wird für die gesamte Lebensdauer einer [IPresentation](../../com.aspose.slides/ipresentation) Instanz gesperrt, bis sie entsorgt wird.

--------------------

[IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) muss auf true gesetzt sein, um dieses Verhalten zu nutzen, sonst wird eine Ausnahme ausgelöst.

--------------------

Dieses Verhalten wird empfohlen, es ist schneller und verbraucht weniger Speicher als [LoadAndRelease](../../com.aspose.slides/presentationlockingbehavior\#LoadAndRelease).