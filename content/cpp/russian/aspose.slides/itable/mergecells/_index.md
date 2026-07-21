---
title: MergeCells()
second_title: Aspose.Slides для C++ справочник API
description: Объединяет соседние ячейки.
type: docs
weight: 261
url: /ru/aspose.slides/itable/mergecells/
---
## ITable::MergeCells(System::SharedPtr\<ICell\>, System::SharedPtr\<ICell\>, bool) метод

Объединяет соседние ячейки.

```cpp
virtual System::SharedPtr<ICell> Aspose::Slides::ITable::MergeCells(System::SharedPtr<ICell> cell1, System::SharedPtr<ICell> cell2, bool allowSplitting)=0
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| cell1 | [System::SharedPtr](../../../system/sharedptr/)\<[ICell](../../icell/)\> | [Cell](../../cell/) для объединения. |
| cell2 | [System::SharedPtr](../../../system/sharedptr/)\<[ICell](../../icell/)\> | [Cell](../../cell/) для объединения. |
| allowSplitting | **bool** | True чтобы разрешить разделение ячеек. |

### Return Value

Возвращаемое значение

Объединённая ячейка.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ICell](../../icell/)
* Класс [ITable](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)