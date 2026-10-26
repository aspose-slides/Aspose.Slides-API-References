---
title: Equals()
second_title: Справочник API Aspose.Slides для C++
description: Определяет, является ли указанный регион идентичным региону, представленному текущим объектом, на указанной поверхности рисования.
type: docs
weight: 157
url: /ru/system.drawing/region/equals/
---
## Region::Equals(const SharedPtr\<Region\>\&, const SharedPtr\<Graphics\>\&) метод

Определяет, является ли указанный регион идентичным региону, представленному текущим объектом, на указанной поверхности рисования.

```cpp
bool System::Drawing::Region::Equals(const SharedPtr<Region> &r, const SharedPtr<Graphics> &g)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| r | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Регион для сравнения с текущим регионом |
| g | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Поверхность рисования |

### Возвращаемое значение

True если внутреннее пространство указанного региона идентично внутреннему пространству региона, представленного текущим объектом, когда применяется преобразование, связанное с параметром **g**; иначе - false

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Region](../)
* Class [Graphics](../../graphics/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)