---
title: SlideShowTransition
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa a transição de apresentação de slides.
type: docs
url: /pt/com.aspose.slides/slideshowtransition/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as interfaces implementadas:**
[com.aspose.slides.ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
```
public class SlideShowTransition extends DomObject<BaseSlide> implements ISlideShowTransition
```

Representa a transição de apresentação de slides.
## Métodos

| Método | Descrição |
| --- | --- |
| [getSound()](#getSound--) | Retorna ou define os dados de áudio incorporados. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Retorna ou define os dados de áudio incorporados. |
| [getSoundMode()](#getSoundMode--) | Define ou retorna o modo de som para a transição de slide. |
| [setSoundMode(int value)](#setSoundMode-int-) | Define ou retorna o modo de som para a transição de slide. |
| [getSoundLoop()](#getSoundLoop--) | Este atributo especifica se o som será repetido até que ocorra o próximo evento sonoro na apresentação. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Este atributo especifica se o som será repetido até que ocorra o próximo evento sonoro na apresentação. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Especifica se um clique do mouse avançará o slide ou não. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Especifica se um clique do mouse avançará o slide ou não. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Este atributo especifica se a apresentação avançará para o próximo slide após um determinado tempo. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Este atributo especifica se a apresentação avançará para o próximo slide após um determinado tempo. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Especifica o tempo, em milissegundos, após o qual a transição deve iniciar. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Especifica o tempo, em milissegundos, após o qual a transição deve iniciar. |
| [getSpeed()](#getSpeed--) | Especifica a velocidade de transição a ser usada ao passar do slide atual para o próximo. |
| [setSpeed(int value)](#setSpeed-int-) | Especifica a velocidade de transição a ser usada ao passar do slide atual para o próximo. |
| [getValue()](#getValue--) | Valor da transição de apresentação de slides. |
| [getType()](#getType--) | Tipo de transição. |
| [setType(int value)](#setType-int-) | Tipo de transição. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Especifica se este som é ou não um som interno. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Especifica se este som é ou não um som interno. |
| [getSoundName()](#getSoundName--) | Especifica um nome legível por humanos para o som da transição. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Especifica um nome legível por humanos para o som da transição. |
| [getDuration()](#getDuration--) | Obtém ou define a duração do efeito de transição de slide em milissegundos. |
| [setDuration(int value)](#setDuration-int-) | Obtém ou define a duração do efeito de transição de slide em milissegundos. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se as duas instâncias SlideShowTransition são iguais. |
| [hashCode()](#hashCode--) | Serve como uma função de hash para um tipo específico, adequada para uso em algoritmos de hash e estruturas de dados como uma tabela hash. |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Retorna ou define os dados de áudio incorporados. Leitura/gravação [IAudio](../../com.aspose.slides/iaudio).

**Retorna:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Retorna ou define os dados de áudio incorporados. Leitura/gravação [IAudio](../../com.aspose.slides/iaudio).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public final int getSoundMode()
```

Define ou retorna o modo de som para a transição de slide. Leitura/gravação [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Retorna:**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public final void setSoundMode(int value)
```

Define ou retorna o modo de som para a transição de slide. Leitura/gravação [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public final boolean getSoundLoop()
```

Este atributo especifica se o som será repetido até que ocorra o próximo evento sonoro na apresentação. Leitura/gravação boolean.

**Retorna:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public final void setSoundLoop(boolean value)
```

Este atributo especifica se o som será repetido até que ocorra o próximo evento sonoro na apresentação. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public final boolean getAdvanceOnClick()
```

Especifica se um clique do mouse avançará o slide ou não. Se este atributo não for especificado, assume-se o valor true. Leitura/gravação boolean.

**Retorna:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public final void setAdvanceOnClick(boolean value)
```

Especifica se um clique do mouse avançará o slide ou não. Se este atributo não for especificado, assume-se o valor true. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public final boolean getAdvanceAfter()
```

Este atributo especifica se a apresentação avançará para o próximo slide após um determinado tempo. Leitura/gravação boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Obtenha a primeira transição de slide
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Verifique se o indicador Avançar slide após está marcado
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Obtenha o valor de tempo de avançar slide após
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
boolean
### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public final void setAdvanceAfter(boolean value)
```

Este atributo especifica se a apresentação avançará para o próximo slide após um determinado tempo. Leitura/gravação boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Obtenha a primeira transição de slide
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Verifique se o sinalizador Avançar slide após está marcado
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Obtenha o valor de tempo de avançar slide após
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public final long getAdvanceAfterTime()
```

Especifica o tempo, em milissegundos, após o qual a transição deve iniciar. Esta configuração pode ser usada em conjunto com o atributo advClick. Se este atributo não for especificado, assume-se que não ocorrerá avanço automático. Leitura/gravação long.

**Retorna:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public final void setAdvanceAfterTime(long value)
```

Especifica o tempo, em milissegundos, após o qual a transição deve iniciar. Esta configuração pode ser usada em conjunto com o atributo advClick. Se este atributo não for especificado, assume-se que não ocorrerá avanço automático. Leitura/gravação long.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public final int getSpeed()
```

Especifica a velocidade de transição a ser usada ao passar do slide atual para o próximo. Leitura/gravação [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Retorna:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public final void setSpeed(int value)
```

Especifica a velocidade de transição a ser usada ao passar do slide atual para o próximo. Leitura/gravação [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public final ITransitionValueBase getValue()
```

Valor da transição de apresentação de slides. Somente leitura [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Retorna:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public final int getType()
```

Tipo de transição. Leitura/gravação [TransitionType](../../com.aspose.slides/transitiontype).

**Retorna:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Tipo de transição. Leitura/gravação [TransitionType](../../com.aspose.slides/transitiontype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public final boolean getSoundIsBuiltIn()
```

Especifica se este som é ou não um som interno. Se este atributo for definido como true, a aplicação geradora será alertada para verificar o atributo name especificado para este som em sua lista de sons internos e então poderá exibir um nome personalizado ou UI conforme necessário. Leitura/gravação boolean.

**Retorna:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public final void setSoundIsBuiltIn(boolean value)
```

Especifica se este som é ou não um som interno. Se este atributo for definido como true, a aplicação geradora será alertada para verificar o atributo name especificado para este som em sua lista de sons internos e então poderá exibir um nome personalizado ou UI conforme necessário. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public final String getSoundName()
```

Especifica um nome legível por humanos para o som da transição. A propriedade Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) deve ser atribuída para obter ou definir o nome do som. Leitura/gravação String.

**Retorna:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public final void setSoundName(String value)
```

Especifica um nome legível por humanos para o som da transição. A propriedade Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) deve ser atribuída para obter ou definir o nome do som. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public final int getDuration()
```

Obtém ou define a duração do efeito de transição de slide em milissegundos. Leitura/gravação int.

Corresponde ao atributo p14:dur do elemento p:transition no esquema PresentationML. Se não estiver definido, a duração será determinada automaticamente com base na propriedade \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) e no tipo de transição.

**Retorna:**
int
### setDuration(int value) {#setDuration-int-}
```
public final void setDuration(int value)
```

Obtém ou define a duração do efeito de transição de slide em milissegundos. Leitura/gravação int.

Corresponde ao atributo p14:dur do elemento p:transition no esquema PresentationML. Se não estiver definido, a duração será determinada automaticamente com base na propriedade \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) e no tipo de transição.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Determina se as duas instâncias SlideShowTransition são iguais. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | java.lang.Object | O SlideShowTransition a ser comparado com o SlideShowTransition atual. |

**Retorna:**
boolean -  **true**  se o SlideShowTransition especificado for igual ao SlideShowTransition atual; caso contrário,  **false** .
### hashCode() {#hashCode--}
```
public int hashCode()
```

Serve como uma função de hash para um tipo específico, adequada para uso em algoritmos de hash e estruturas de dados como uma tabela hash.

**Retorna:**
int - 23454

Sobrescrito para satisfazer o compilador. Sempre retorna um valor constante porque o objeto é mutável.