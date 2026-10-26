---
title: ILegacyDiagram
second_title: Справочник API Aspose.Slides для Java
description: Представляет устаревший объект диаграммы
type: docs
url: /ru/com.aspose.slides/ilegacydiagram/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

Представляет устаревший объект диаграммы
## Методы

| Метод | Описание |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Преобразует устаревший diagram в редактируемый объект SmartArt. |
| [convertToGroupShape()](#convertToGroupShape--) | Преобразует устаревший diagram в редактируемый объект GroupShape. |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```

Преобразует устаревший diagram в редактируемый объект SmartArt. Созданный объект SmartArt добавляется к родительской group shape в том же положении.

**Возвращаемое значение:**
[ISmartArt](../../com.aspose.slides/ismartart) - Созданный объект SmartArt.
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```

Преобразует устаревший diagram в редактируемый объект GroupShape. Созданный объект GroupShape добавляется к родительской group shape в том же положении.

**Возвращаемое значение:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Созданный объект GroupShape.