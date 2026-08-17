---
title: IHyperlinkQueries
second_title: Aspose.Slides for Java API Reference
description: Provide easy access to contained hyperlinks.
type: docs
url: /ru/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

Обеспечивает простой доступ к содержащимся гиперссылкам.

## Методы

| Метод | Описание |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | Получить все подпредметы IHyperlinkContainer, содержащие ненулевой HyperlinkClick. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | Получить все подпредметы IHyperlinkContainer, содержащие ненулевой HyperlinkMouseOver. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | Получить все подпредметы IHyperlinkContainer, содержащие ненулевой HyperlinkMouseOver. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | Удаляет все содержащие HyperlinkClick и HyperlinkMouseOver гиперссылки (во всех подпредметах IHyperlinkContainer). |

### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

Получить все подпредметы IHyperlinkContainer, содержащие ненулевой HyperlinkClick. С данным объектом IHyperlinkContainer вы можете управлять его гиперссылкой (читать, обновлять или удалять). Смотрите интерфейс IHyperlinkContainer.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Все подпредметы IHyperlinkContainer, содержащие ненулевой HyperlinkClick

### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

Получить все подпредметы IHyperlinkContainer, содержащие ненулевой HyperlinkMouseOver. С данным объектом IHyperlinkContainer вы можете управлять его гиперссылкой (читать, обновлять или удалять). Смотрите интерфейс IHyperlinkContainer.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Все подпредметы IHyperlinkContainer, содержащие ненулевой HyperlinkMouseOver

### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

Получить все подпредметы IHyperlinkContainer, содержащие ненулевой HyperlinkMouseOver. С данным объектом IHyperlinkContainer вы можете управлять его гиперссылкой (читать, обновлять или удалять). Смотрите интерфейс IHyperlinkContainer.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Все подпредметы IHyperlinkContainer, содержащие ненулевой HyperlinkMouseOver

### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```

Удаляет все содержащие HyperlinkClick и HyperlinkMouseOver гиперссылки (во всех подпредметах IHyperlinkContainer).