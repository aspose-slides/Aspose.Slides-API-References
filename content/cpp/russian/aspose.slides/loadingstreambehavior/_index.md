---
title: LoadingStreamBehavior
second_title: Aspose.Slides для C++ API Reference
description: "Передаваемый в метод System::IO::Stream рассматривается как Binary Large Object (BLOB) (см. описание IBlobManagementOptions). Значения этого перечисления определяют, как следует обрабатывать System::IO::Stream при передаче его в метод. В зависимости от требований могут быть приняты различные решения для обеспечения наиболее эффективного поведения."
type: docs
weight: 6735
url: /ru/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior enum

Передаваемый в метод [System::IO::Stream](../../system.io/stream/) рассматривается как Binary Large Object (BLOB) (см. описание [IBlobManagementOptions](../iblobmanagementoptions/)). Значения этого перечисления определяют, как следует обрабатывать [System::IO::Stream](../../system.io/stream/) при передаче его в метод. В зависимости от требований можно принимать различные решения для обеспечения наибольшей эффективности поведения.

```cpp
enum class LoadingStreamBehavior
```

### Values

| Имя | Значение | Описание |
| --- | --- | --- |
| ReadStreamAndRelease | 0 | Поток будет прочитан до конца и затем освобождён – т.е. будет гарантировано, что этот поток больше не будет использоваться экземпляром [IPresentation](../ipresentation/) в будущем. Его может закрыть клиентский код или использовать любым другим способом. |
| KeepLocked | 1 | Поток будет заблокирован внутри объекта [IPresentation](../ipresentation/), т.е. право собственности на поток будет передано. Объект [IPresentation](../ipresentation/) будет отвечать за корректное освобождение потока, когда сам будет уничтожен. Такое поведение особенно полезно, когда необходимо сериализовать большой файл BLOB (например, большое видео или аудио – см. описание [IBlobManagementOptions](../iblobmanagementoptions/)) и избежать загрузки этого файла в память или других проблем с производительностью. Вы можете просто открыть [System::IO::FileStream](../../system.io/filestream/) для этого файла и передать его в метод, выбрав LoadingStreamBehavior [LoadingStreamBehavior::KeepLocked](./). |

## См. также

* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)