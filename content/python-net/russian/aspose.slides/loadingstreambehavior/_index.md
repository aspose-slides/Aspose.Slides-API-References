---
title: LoadingStreamBehavior enumeration
second_title: Справочник API Aspose.Slides for Python через .NET
description: 
type: docs
url: /ru/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior перечисление

Объект **io.RawIOBase**, передаваемый методу, рассматривается как бинарный крупный объект (BLOB) (см. описание [`IBlobManagementOptions`](/slides/python-net/ru/aspose.slides/iblobmanagementoptions)). Значения этого перечисления определяют, как следует обрабатывать **io.RawIOBase**, когда он передаётся методу. В зависимости от требований могут приниматься различные решения для обеспечения наибольшей эффективности.

Тип LoadingStreamBehavior раскрывает следующие члены:

## Поля

| Поле | Описание |
| :- | :- |
| READ_STREAM_AND_RELEASE | Поток будет прочитан до конца, а затем освобождён — то есть будет гарантировано, что этот поток <br/>            не будет использоваться экземпляром [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation) в будущем. Он может быть закрыт клиентским <br/>            кодом или использован иным способом. |
| KEEP_LOCKED | Поток будет заблокирован внутри объекта [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation), то есть владение потоком будет передано. Объект [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation) будет отвечать за <br/>            корректное освобождение потока, когда этот объект будет уничтожен сам. <br/>            Такое поведение чрезвычайно полезно, когда необходимо сериализовать большой BLOB-файл (например, большой <br/>            видео- или аудио-файл — см. описание [`IBlobManagementOptions`](/slides/python-net/ru/aspose.slides/iblobmanagementoptions)) и требуется избежать загрузки <br/>            этого файла в память или других проблем с производительностью. Вы можете просто открыть **System.IO.FileStream** <br/>            для этого файла и передать его методу, выбрав [`LoadingStreamBehavior.KEEP_LOCKED`](/slides/python-net/ru/aspose.slides/loadingstreambehavior/KEEP_LOCKED) LoadingStreamBehavior. |

### См. также
* класс [`IBlobManagementOptions`](/slides/python-net/ru/aspose.slides/iblobmanagementoptions)
* класс [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)