---
title: AddPath()
second_title: Aspose.Slides для C++ справочник API
description: Добавляет указанный путь к пути, представленному текущим объектом.
type: docs
weight: 222
url: /ru/system.drawing.drawing2d/graphicspath/addpath/
---
## GraphicsPath::AddPath(const SharedPtr\<GraphicsPath\>\&, bool) метод

Добавляет указанный путь к пути, представленному текущим объектом.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPath(const SharedPtr<GraphicsPath> &path, bool connect)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../)\>\& | Путь для добавления |
| connect | **bool** | True указывает, что последняя первая фигура в **path** является частью последней фигуры пути, представленного текущим объектом; false указывает, что первая фигура в **path** и последняя фигура пути, представленного текущим объектом, являются отдельными фигурами |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [GraphicsPath](../)
* Пространство имён [System::Drawing::Drawing2D](../../)
* Библиотека [Aspose.Slides](../../../)