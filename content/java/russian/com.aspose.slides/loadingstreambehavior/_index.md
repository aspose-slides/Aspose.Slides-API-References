---
title: LoadingStreamBehavior
second_title: Справочник API Aspose.Slides для Java
description: java.io.InputStream, передаваемый в метод, рассматривается как Binary Large Object (BLOB) (см. описание).
type: docs
url: /ru/com.aspose.slides/loadingstreambehavior/
---
**Наследование:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

Передаваемый в метод java.io.InputStream считается Binary Large Object (BLOB) (см. описание [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)). Значения этого перечисления определяют, как следует обрабатывать java.io.InputStream при передаче в метод. В зависимости от требований могут быть приняты разные решения для обеспечения наибольшей эффективности.
## Поля

| Поле | Описание |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | Поток будет прочитан до конца, а затем освобождён — т. е. |
| [KeepLocked](#KeepLocked) | Поток будет заблокирован внутри объекта [IPresentation](../../com.aspose.slides/ipresentation) — т. е. |
### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

Поток будет прочитан до конца, а затем освобождён — т. е. будет гарантировано, что этот поток больше не будет использоваться экземпляром [IPresentation](../../com.aspose.slides/ipresentation) в будущем. Он может быть закрыт клиентским кодом или использован любым другим способом.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // поток можно закрыть, он больше не нужен объекту "pres".
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```


### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

Поток будет заблокирован внутри объекта [IPresentation](../../com.aspose.slides/ipresentation) — т. е. право собственности на поток будет передано. Объект [IPresentation](../../com.aspose.slides/ipresentation) будет отвечать за корректное освобождение потока, когда этот объект будет уничтожен. Такое поведение особенно полезно, когда необходимо сериализовать большой BLOB-файл (например, большой видеофайл или аудио — см. описание [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)) и избежать загрузки этого файла в память или других проблем с производительностью. Вы можете просто открыть java.io.FileInputStream для этого файла и передать его в метод, выбрав [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // Вы не должны закрывать поток или взаимодействовать с ним каким-либо другим способом, это приведет к ошибке в методе Save.
>    // Поток fileStream будет использоваться для сохранения, что предотвратит высокое потребление памяти
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```
