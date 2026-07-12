---
title: IPortionFormat
second_title: Aspose.Slides para Android via Referência da API Java
description: Esta classe contém as propriedades de formatação de porção de texto.
type: docs
url: /pt/com.aspose.slides/iportionformat/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

Esta classe contém as propriedades de formatação de porção de texto. Ao contrário de [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), todas as propriedades desta classe são graváveis.

--------------------

Esta classe é usada para retornar e manipular as propriedades de formatação de porção de texto definidas para a porção específica. Isso significa que nenhuma herança é aplicada ao obter valores, portanto, na maioria dos casos você receberá valores significando "undefined".

Para obter os valores efetivos dos parâmetros de formatação, incluindo os herdados, você precisa usar o método [getEffective](../../com.aspose.slides/iportionformat\#getEffective) que retorna uma instância [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).
## Métodos

| Método | Descrição |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Retorna ou define o identificador de bookmark. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Retorna ou define o identificador de bookmark. |
| [getSmartTagClean()](#getSmartTagClean--) | Determina se a smart tag deve ser limpa. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Determina se a smart tag deve ser limpa. |
| [getEffective()](#getEffective--) | Obtém os dados de formatação de porção efetiva com a herança aplicada. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

Retorna ou define o identificador de bookmark. Leitura/gravação String.

**Retorna:**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```

Retorna ou define o identificador de bookmark. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

Determina se a smart tag deve ser limpa. Nenhuma herança aplicada. Leitura/gravação boolean.

**Retorna:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```

Determina se a smart tag deve ser limpa. Nenhuma herança aplicada. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```

Obtém os dados de formatação de porção efetiva com a herança aplicada.

**Retorna:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).