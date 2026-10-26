---
title: ILegacyDiagram
second_title: Aspose.Slides для Android через Java API Reference
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
| [convertToSmartArt()](#convertToSmartArt--) | Преобразует устаревшую диаграмму в редактируемый объект SmartArt. |
| [convertToGroupShape()](#convertToGroupShape--) | Преобразует устаревшую диаграмму в редактируемую группу фигур. |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```


Преобразует устаревшую диаграмму в редактируемый объект SmartArt. Созданный объект SmartArt добавляется к родительской группе фигур в том же положении.

**Возвращаемое значение:**
[ISmartArt](../../com.aspose.slides/ismartart) - Созданный объект SmartArt.
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```


Преобразует устаревшую диаграмму в редактируемую группу фигур. Созданный объект GroupShape добавляется к родительской группе фигур в том же положении.

**Возвращаемое значение:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Созданный объект GroupShape.