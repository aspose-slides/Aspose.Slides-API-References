---
title: ColorTranslator
second_title: Aspose.Slides para C++ Referência da API
description: "Realiza traduções de cores. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie uma instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 66
url: /pt/system.drawing/colortranslator/
---
## ColorTranslator classe


Realiza traduções de cores. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie uma instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class ColorTranslator
```

## Métodos

| Método | Descrição |
| --- | --- |
| static [Color](../color/) [FromHtml](./fromhtml/)(const [System::String](../../system/string/)\&) | Converte a representação de cor HTML especificada para o objeto [Color](../color/) equivalente. |
| static [Color](../color/) [FromWin32](./fromwin32/)(int) | Converte a cor [Windows](../../system.windows/) especificada para o objeto [Color](../color/) equivalente. |
| static [String](../../system/string/) [ToHtml](./tohtml/)(const [Color](../color/)\&) | Converte o objeto [Color](../color/) especificado para a representação em string da cor HTML equivalente. |
## Veja Também

* Espaço de nomes [System::Drawing](../)
* Biblioteca [Aspose.Slides](../../)