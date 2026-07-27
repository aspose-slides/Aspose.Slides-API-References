---
title: Equals< float, float >()
second_title: Referência da API Aspose.Slides para C++
description: "Especialização para valores de ponto flutuante de precisão simples. Embora dois NaNs de ponto flutuante sejam definidos pela IEC 60559:1989 para sempre serem comparados como diferentes, o contrato para System.Object.Equals requer que as sobreposições satisfaçam os requisitos para um operador de equivalência. Portanto, System.Double.Equals e System.Single.Equals retornam True ao comparar dois NaNs, enquanto o operador de igualdade retorna False nesse caso, conforme exigido pelo padrão."
type: docs
weight: 2705
url: /pt/system/equals_less_float,_float__greater/
---
## System::Equals< float, float >(const float\&, const float\&) function

Especialização para valores de ponto flutuante de precisão simples. Embora dois NaNs de ponto flutuante sejam definidos pela IEC 60559:1989 para sempre serem comparados como diferentes, o contrato para [System.Object.Equals](../object/equals/) exige que as substituições satisfaçam os requisitos para um operador de equivalência. Portanto, System.Double.Equals e System.Single.Equals retornam True ao comparar dois NaNs, enquanto o operador de igualdade retorna False nesse caso, conforme exigido pelo padrão.

```cpp
bool System::Equals<float, float>(const float &a, const float &b)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| a | const **float**\& | O primeiro comparando |
| b | const **float**\& | O segundo comparando |

### Valor de retorno

True se ambos os valores são NaN ou são iguais, caso contrário - false

## Veja também

* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)