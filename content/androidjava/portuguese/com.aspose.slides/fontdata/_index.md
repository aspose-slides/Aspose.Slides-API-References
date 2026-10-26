---
title: FontData
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma definição de fonte.
type: docs
url: /pt/com.aspose.slides/fontdata/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)
```
public final class FontData implements IFontData
```

Representa uma definição de fonte. Imutável.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | Cria um novo objeto FontData com o nome da fonte especificado. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getFontName()](#getFontName--) | Retorna o nome da fonte. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Retorna o nome da fonte, substituindo a referência de tema por uma fonte real usada. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se duas instâncias de FontData são iguais. |
| [hashCode()](#hashCode--) | Funciona como uma função de hash para um tipo específico, adequada para uso em algoritmos de hash e estruturas de dados como uma tabela de hash. |
| [toString()](#toString--) | Retorna a representação em forma de string. |
### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```

Cria um novo objeto FontData com o nome da fonte especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontName | java.lang.String | Nome da fonte. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```

Retorna o nome da fonte. Leitura/gravação String.

**Retorna:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```

Retorna o nome da fonte, substituindo a referência de tema por uma fonte real usada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Tema do qual o nome da fonte temático deve ser obtido. Cabe ao chamador fornecer um valor correto. Veja [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**Retorna:**
java.lang.String - Nome da fonte.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Determina se duas instâncias de FontData são iguais.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | java.lang.Object | O FontData a ser comparado com o FontData atual. |

**Retorna:**
boolean - **true** se o FontData especificado for igual ao FontData atual; caso contrário, **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Funciona como uma função de hash para um tipo específico, adequada para uso em algoritmos de hash e estruturas de dados como uma tabela de hash.

**Retorna:**
int - Código hash do FontData.
### toString() {#toString--}
```
public String toString()
```

Retorna a representação em forma de string.

**Retorna:**
java.lang.String - Representação em forma de string.