---
title: Insert()
second_title: Referência da API Aspose.Slides para C++
description: Insere um MathElement na coleção no índice especificado.
type: docs
weight: 157
url: /pt/aspose.slides.mathtext/mathblock/insert/
---
## MathBlock::Insert(int32_t, System::SharedPtr\<IMathElement\>) método

Insere um MathElement na coleção no índice especificado.

```cpp
void Aspose::Slides::MathText::MathBlock::Insert(int32_t index, System::SharedPtr<IMathElement> item) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero no qual o MathElement deve ser inserido. |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | O MathElement a ser inserido. |
## Observações



Exemplo: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathBlock](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)