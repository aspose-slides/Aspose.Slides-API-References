---
title: LoadingStreamBehavior
second_title: Справочник Aspose.Slides для Android через Java API
description: java.io.InputStream, передаваемый в метод, рассматривается как Binary Large Object (BLOB), см. описание.
type: docs
url: /ru/com.aspose.slides/loadingstreambehavior/
---
**Наследование:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

java.io.InputStream, передаваемый в метод, рассматривается как Binary Large Object (BLOB) (см. описание [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)). Значения этой перечисления определяют, как следует обрабатывать java.io.InputStream при передаче в метод. В зависимости от требований могут быть приняты разные решения для обеспечения наибольшей эффективности поведения.

## Поля

| Поле | Описание |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | Поток будет прочитан до конца и затем освобожден — то есть |
| [KeepLocked](#KeepLocked) | Поток будет заблокирован внутри объекта [IPresentation](../../com.aspose.slides/ipresentation), то есть |

### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

Поток будет прочитан до конца и затем освобожден — то есть будет гарантировано, что этот поток не будет использован экземпляром [IPresentation](../../com.aspose.slides/ipresentation) в будущем. Его можно закрыть клиентским кодом или использовать любым другим способом.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // Поток можно закрыть, он больше не нужен объекту "pres".
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```


### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

Поток будет заблокирован внутри объекта [IPresentation](../../com.aspose.slides/ipresentation), то есть право собственности на поток будет передано. Объект [IPresentation](../../com.aspose.slides/ipresentation) будет отвечать за корректное освобождение потока, когда этот объект будет освобождён сам. Такое поведение чрезвычайно полезно, когда необходимо сериализовать большой файл BLOB (например, большое видео или аудио — см. описание [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)) и избежать загрузки этого файла в память или других проблем производительности. Вы можете просто открыть java.io.FileInputStream для этого файла и передать его методу, выбирая [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // Вы не должны закрывать поток или взаимодействовать с ним каким-либо другим способом, это приведёт к ошибке в методе Save.
>    // FileStream будет использоваться для сохранения, что предотвратит высокое потребление памяти
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```
