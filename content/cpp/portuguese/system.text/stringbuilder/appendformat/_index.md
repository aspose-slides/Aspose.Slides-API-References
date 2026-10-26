---
title: AppendFormat()
second_title: Referência da API Aspose.Slides for C++
description: Anexa string formatada ao construtor.
type: docs
weight: 131
url: /pt/system.text/stringbuilder/appendformat/
---
## StringBuilder::AppendFormat(const String&, const TArgs&...) método


Anexa string formatada ao construtor.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const String &format, const TArgs &... args)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TArgs | Tipo dos argumentos. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| format | const [String](../../../system/string/)& | String de formato. |
| args | const TArgs&... | Argumentos a inserir nas posições da string de formato. |

### Valor de Retorno

Este ponteiro.

## StringBuilder::AppendFormat(const SharedPtr\<IFormatProvider\>&, const String&, const TArgs&...) método


Anexa string formatada ao construtor.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const SharedPtr<IFormatProvider> &fp, const String &format, const TArgs &... args)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TArgs | Tipo dos argumentos. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fp | const [SharedPtr](../../../system/sharedptr/)\<[IFormatProvider](../../../system/iformatprovider/)\>& | Provedor de formato; ignorado. |
| format | const [String](../../../system/string/)& | String de formato. |
| args | const TArgs&... | Argumentos a inserir nas posições da string de formato. |

### Valor de Retorno

Este ponteiro.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Class [IFormatProvider](../../../system/iformatprovider/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)