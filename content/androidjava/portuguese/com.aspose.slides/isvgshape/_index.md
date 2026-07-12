---
title: ISvgShape
second_title: Aspose.Slides for Android via Java API Reference
description: Representa opções para forma SVG.
type: docs
url: /pt/com.aspose.slides/isvgshape/
---```
public interface ISvgShape
```

Representa opções para forma SVG.
## Métodos

| Método | Descrição |
| --- | --- |
| [setEventHandler(int eventType, String handler)](#setEventHandler-int-java.lang.String-) | Sets event handler for the shape |
| [getId()](#getId--) | Sets or gets id for the shape |
| [setId(String value)](#setId-java.lang.String-) | Sets or gets id for the shape |
### setEventHandler(int eventType, String handler) {#setEventHandler-int-java.lang.String-}
```
public abstract void setEventHandler(int eventType, String handler)
```


Define o manipulador de evento para a forma

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| eventType | int | Tipo de evento. |
| handler | java.lang.String | Função Javascript para tratar o evento. Valor nulo remove o manipulador. |

### getId() {#getId--}
```
public abstract String getId()
```


Define ou obtém o id da forma

**Retorna:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```


Define ou obtém o id da forma

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |