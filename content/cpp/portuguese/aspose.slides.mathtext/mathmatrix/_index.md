---
title: MathMatrix
second_title: Referência da API Aspose.Slides para C++
description: Especifica o objeto Matrix, constituído por elementos filhos organizados em uma ou mais linhas e colunas. É importante observar que matrizes não possuem delimitadores incorporados. Para colocar a matriz entre colchetes, deve-se usar o objeto delimitador (IMathDelimiter). Argumentos nulos podem ser usados para criar lacunas nas matrizes.
type: docs
weight: 950
url: /pt/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix classe


Especifica o objeto Matrix, constituído por elementos filhos organizados em uma ou mais linhas e colunas. É importante observar que matrizes não possuem delimitadores embutidos. Para colocar a matriz entre colchetes, deve-se usar o objeto delimitador ([IMathDelimiter](../imathdelimiter/)). Argumentos nulos podem ser usados para criar lacunas nas matrizes.

```cpp
class MathMatrix : public Aspose::Slides::MathText::MathElementBase,
                   public Aspose::Slides::MathText::IMathMatrix,
                   public Aspose::Slides::MathText::IHasControlCharacterProperties
```

## Métodos

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](../mathelementbase/accent/)(char16_t) override | Define um acento (um caractere no topo deste elemento) |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Usa a função especificada usando esta instância como argumento |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::String](../../system/string/)) override | Usa a função especificada usando esta instância como argumento |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) override | Usa a função especificada usando esta instância como argumento |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Usa a função especificada usando esta instância como argumento e um argumento adicional especificado |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) override | Usa a função especificada usando esta instância como argumento e um argumento adicional especificado |
| void [DeleteColumn](./deletecolumn/)(**int32_t**) override | Exclui a coluna especificada |
| void [DeleteRow](./deleterow/)(**int32_t**) override | Exclui a linha especificada |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Cria uma fração com este numerador e denominador especificado |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/)) override | Cria uma fração com este numerador e denominador especificado |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathFractionTypes](../mathfractiontypes/)) override | Cria uma fração do tipo especificado com este numerador e denominador especificado |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) override | Cria uma fração do tipo especificado com este numerador e denominador especificado |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../mathelementbase/enclose/)() override | Envolve um elemento matemático entre parênteses |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../mathelementbase/enclose/)(char16_t, char16_t) override | Envolve um elemento matemático em caracteres especificados, como parênteses ou outros caracteres como moldura |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Usa uma função de um argumento usando esta instância como nome da função |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::String](../../system/string/)) override | Usa uma função de um argumento usando esta instância como nome da função |
| [MathVerticalAlignment](../mathverticalalignment/) [get_BaseJustification](./get_basejustification/)() override | Especifica a justificação vertical em relação ao texto circundante. Valores possíveis são superior, inferior e central. Padrão: Center |
| **int32_t** [get_ColumnCount](./get_columncount/)() override | Número de colunas na matriz |
| **uint32_t** [get_ColumnGap](./get_columngap/)() override | O valor do espaçamento horizontal entre colunas de uma matriz; Se a ColumnGapRule estiver definida como 3 ("Exactly"), a unidade é interpretada como twips (1/20 de ponto). Se a ColumnGapRule estiver definida como 4 ("Multiple"), a unidade é interpretada como número de incrementos de 0,5 em. Em outros casos é ignorado. Padrão: 0 |
| [MathSpacingRules](../mathspacingrules/) [get_ColumnGapRule](./get_columngaprule/)() override | O tipo de espaçamento horizontal entre colunas de uma matriz; As unidades de espaçamento horizontal podem ser ems ou pontos (armazenados como twips). Padrão: SingleSpacingGap (0) |
| **bool** [get_HidePlaceholders](./get_hideplaceholders/)() override | Oculta os marcadores de posição para elementos vazios da matriz. Padrão: false |
| **uint32_t** [get_MinColumnWidth](./get_mincolumnwidth/)() override | Largura mínima da coluna em twips (1/20 de ponto). O espaçamento de preenchimento (também referido como "Column Gap" ou "Gap Width") é adicionado ao MinColumnWidth para determinar o espaçamento total da matriz [Column](../../aspose.slides/column/) (distância entre as mesmas bordas de colunas diferentes). Padrão: 0. |
| **int32_t** [get_RowCount](./get_rowcount/)() override | Número de linhas na matriz |
| **uint32_t** [get_RowGap](./get_rowgap/)() override | O valor do espaçamento vertical entre linhas de uma matriz; Se a RowGapRule estiver definida como 3 ("Exactly"), a unidade é interpretada como twips (1/20 de ponto). Se a RowGapRule estiver definida como 4 ("Multiple"), a unidade é interpretada como meia-linha. Padrão: 0 |
| [MathSpacingRules](../mathspacingrules/) [get_RowGapRule](./get_rowgaprule/)() override | O tipo de espaçamento vertical entre linhas de uma matriz; As unidades de espaçamento vertical podem ser linhas ou pontos (armazenados como twips). Padrão: SingleSpacingGap (0) |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\> [GetChildren](./getchildren/)() override | Obtém os elementos filhos |
| [MathHorizontalAlignment](../mathhorizontalalignment/) [GetColumnAlignment](./getcolumnalignment/)(**int32_t**) override | Obtém o alinhamento horizontal da coluna especificada |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo do método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hashing de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analogo da chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)() override | Coloca este elemento em um grupo usando uma chave inferior |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) override | Coloca este elemento em um grupo usando um caractere de agrupamento, como chave inferior ou outro |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [idx_get](./idx_get/)(**int32_t**, **int32_t**) override | Elemento da matriz |
| void [idx_set](./idx_set/)(**int32_t**, **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Elemento da matriz |
| void [InsertColumnAfter](./insertcolumnafter/)(**int32_t**) override | Insere uma nova coluna após a especificada. Inicialmente, todos os elementos na nova coluna são nulos. |
| void [InsertColumnBefore](./insertcolumnbefore/)(**int32_t**) override | Insere uma nova coluna antes da especificada. Inicialmente, todos os elementos na nova coluna são nulos. |
| void [InsertRowAfter](./insertrowafter/)(**int32_t**) override | Insere uma nova linha após a especificada. Inicialmente, todos os elementos na nova linha são nulos. |
| void [InsertRowBefore](./insertrowbefore/)(**int32_t**) override | Insere uma nova linha antes da especificada. Inicialmente, todos os elementos na nova linha são nulos. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathLimitLocations](../mathlimitlocations/)) override | Calcula a integral |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Calcula a integral |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/)) override | Calcula a integral sem limites |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) override | Calcula a integral |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | Calcula a integral |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analogo do operador C# 'is'. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Une um elemento matemático e forma um bloco matemático |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::String](../../system/string/)) override | Une um texto matemático e forma um bloco matemático |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
|  [MathMatrix](./mathmatrix/)(**int32_t**, **int32_t**) | Inicializa uma nova instância da classe [MathMatrix](./). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo do método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonagem de tipos personalizados. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Cria um operador N-ário |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | Cria um operador N-ário |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias em subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias em subclasses. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](../mathelementbase/overbar/)() override | Define uma barra no topo deste elemento |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Especifica a raiz matemática do grau dado a partir do argumento especificado. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::String](../../system/string/)) override | Especifica a raiz matemática do grau dado a partir do argumento especificado. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_BaseJustification](./set_basejustification/)([MathVerticalAlignment](../mathverticalalignment/)) override | Especifica a justificação vertical em relação ao texto circundante. Valores possíveis são superior, inferior e central. Padrão: Center |
| void [set_ColumnGap](./set_columngap/)(**uint32_t**) override | O valor do espaçamento horizontal entre colunas de uma matriz; Se a ColumnGapRule estiver definida como 3 ("Exactly"), a unidade é interpretada como twips (1/20 de ponto). Se a ColumnGapRule estiver definida como 4 ("Multiple"), a unidade é interpretada como número de incrementos de 0,5 em. Em outros casos é ignorado. Padrão: 0 |
| void [set_ColumnGapRule](./set_columngaprule/)([MathSpacingRules](../mathspacingrules/)) override | O tipo de espaçamento horizontal entre colunas de uma matriz; As unidades de espaçamento horizontal podem ser ems ou pontos (armazenados como twips). Padrão: SingleSpacingGap (0) |
| void [set_HidePlaceholders](./set_hideplaceholders/)(**bool**) override | Oculta os marcadores de posição para elementos vazios da matriz. Padrão: false |
| void [set_MinColumnWidth](./set_mincolumnwidth/)(**uint32_t**) override | Largura mínima da coluna em twips (1/20 de ponto). O espaçamento de preenchimento (também referido como "Column Gap" ou "Gap Width") é adicionado ao MinColumnWidth para determinar o espaçamento total da matriz [Column](../../aspose.slides/column/) (distância entre as mesmas bordas de colunas diferentes). Padrão: 0. |
| void [set_RowGap](./set_rowgap/)(**uint32_t**) override | O valor do espaçamento vertical entre linhas de uma matriz; Se a RowGapRule estiver definida como 3 ("Exactly"), a unidade é interpretada como twips (1/20 de ponto). Se a RowGapRule estiver definida como 4 ("Multiple"), a unidade é interpretada como meia-linha. Padrão: 0 |
| void [set_RowGapRule](./set_rowgaprule/)([MathSpacingRules](../mathspacingrules/)) override | O tipo de espaçamento vertical entre linhas de uma matriz; As unidades de espaçamento vertical podem ser linhas ou pontos (armazenados como twips). Padrão: SingleSpacingGap (0) |
| void [SetColumnAlignment](./setcolumnalignment/)(**int32_t**, [MathHorizontalAlignment](../mathhorizontalalignment/)) override | Define o alinhamento horizontal da coluna especificada |
| void [SetColumnsAlignment](./setcolumnsalignment/)(**int32_t**, **uint32_t**, [MathHorizontalAlignment](../mathhorizontalalignment/)) override | Define o alinhamento horizontal das colunas especificadas |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../mathelementbase/setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Obtém o limite inferior |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../mathelementbase/setlowerlimit/)([System::String](../../system/string/)) override | Obtém o limite inferior |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../mathelementbase/setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Cria subscrito |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../mathelementbase/setsubscript/)([System::String](../../system/string/)) override | Cria subscrito |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../mathelementbase/setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Cria subscrito e sobrescrito à esquerda |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../mathelementbase/setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) override | Cria subscrito e sobrescrito à esquerda |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../mathelementbase/setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Cria subscrito e sobrescrito à direita |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../mathelementbase/setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) override | Cria subscrito e sobrescrito à direita |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../mathelementbase/setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Cria sobrescrito |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../mathelementbase/setsuperscript/)([System::String](../../system/string/)) override | Cria sobrescrito |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Obtém o limite superior |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::String](../../system/string/)) override | Obtém o limite superior |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)() override | Coloca este elemento em uma caixa de borda |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) override | Coloca este elemento em uma caixa de borda |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](../imathbox/)\> [ToBox](../mathelementbase/tobox/)() override | Coloca este elemento em uma caixa não visual (agrupamento lógico) que é usada para agrupar componentes de uma equação ou outra instância de texto matemático. Um objeto em caixa pode (por exemplo) servir como um emulador de operador com ou sem ponto de alinhamento, servir como ponto de quebra de linha, ou ser agrupado de forma a não permitir quebras de linha dentro. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](../mathelementbase/tomatharray/)() override | Coloca em um array vertical |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo do método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](../mathelementbase/underbar/)() override | Define uma barra na parte inferior deste elemento |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Observações


Exemplo: 
```cpp
System::SharedPtr<IMathMatrix> matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## Veja Também

* Classe [MathElementBase](../mathelementbase/)
* Classe [IMathMatrix](../imathmatrix/)
* Classe [IHasControlCharacterProperties](../ihascontrolcharacterproperties/)
* Namespace [Aspose::Slides::MathText](../)
* Biblioteca [Aspose.Slides](../../)