---
title: ISlideShowTransition
second_title: Aspose.Slides for Android via Java API Reference
description: Represents slide show transition.
type: docs
url: /pt/com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
```

Representa a transição de apresentação de slides.
## Métodos

| Method | Description |
| --- | --- |
| [getSound()](#getSound--) | Retorna ou define os dados de áudio incorporados. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Retorna ou define os dados de áudio incorporados. |
| [getSoundMode()](#getSoundMode--) | Define ou retorna o modo de som para a transição de slide. |
| [setSoundMode(int value)](#setSoundMode-int-) | Define ou retorna o modo de som para a transição de slide. |
| [getSoundLoop()](#getSoundLoop--) | Este atributo especifica se o som será repetido até que ocorra o próximo evento de som na apresentação. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Este atributo especifica se o som será repetido até que ocorra o próximo evento de som na apresentação. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Especifica se um clique do mouse avançará o slide ou não. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Especifica se um clique do mouse avançará o slide ou não. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Este atributo especifica se a apresentação avançará para o próximo slide após um determinado tempo. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Este atributo especifica se a apresentação avançará para o próximo slide após um determinado tempo. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Especifica o tempo, em milissegundos, após o qual a transição deve começar. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Especifica o tempo, em milissegundos, após o qual a transição deve começar. |
| [getSpeed()](#getSpeed--) | Especifica a velocidade de transição que será usada ao transitar do slide atual para o próximo. |
| [setSpeed(int value)](#setSpeed-int-) | Especifica a velocidade de transição que será usada ao transitar do slide atual para o próximo. |
| [getValue()](#getValue--) | Valor da transição de apresentação. |
| [getType()](#getType--) | Tipo de transição. |
| [setType(int value)](#setType-int-) | Tipo de transição. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Especifica se este som é ou não um som incorporado. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Especifica se este som é ou não um som incorporado. |
| [getSoundName()](#getSoundName--) | Especifica um nome legível por humanos para o som da transição. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Especifica um nome legível por humanos para o som da transição. |
| [getDuration()](#getDuration--) | Obtém ou define a duração do efeito de transição do slide em milissegundos. |
| [setDuration(int value)](#setDuration-int-) | Obtém ou define a duração do efeito de transição do slide em milissegundos. |
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Retorna ou define os dados de áudio incorporados. Leitura/Gravação [IAudio](../../com.aspose.slides/iaudio).

**Retorna:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

Retorna ou define os dados de áudio incorporados. Leitura/Gravação [IAudio](../../com.aspose.slides/iaudio).

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```

Define ou retorna o modo de som para a transição de slide. Leitura/Gravação [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Retorna:**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```

Define ou retorna o modo de som para a transição de slide. Leitura/Gravação [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```

Este atributo especifica se o som será repetido até que ocorra o próximo evento de som na apresentação. Leitura/Gravação boolean.

**Retorna:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```

Este atributo especifica se o som será repetido até que ocorra o próximo evento de som na apresentação. Leitura/Gravação boolean.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```

Especifica se um clique do mouse avançará o slide ou não. Se este atributo não for especificado, assume-se o valor true. Leitura/Gravação boolean.

**Retorna:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```

Especifica se um clique do mouse avançará o slide ou não. Se este atributo não for especificado, assume-se o valor true. Leitura/Gravação boolean.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```

Este atributo especifica se a apresentação avançará para o próximo slide após um determinado tempo. Leitura/Gravação boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Obter a primeira transição de slide
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Verificar se a flag Avançar slide após está marcada
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Obter o valor do tempo de avançar slide após
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
public abstract void setAdvanceAfter(boolean value)
```

Este atributo especifica se a apresentação avançará para o próximo slide após um determinado tempo. Leitura/Gravação boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Obter a primeira transição de slide
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Verificar se a flag Avançar slide após está marcada
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Obter o valor do tempo de avançar slide após
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public abstract long getAdvanceAfterTime()
```

Especifica o tempo, em milissegundos, após o qual a transição deve começar. Essa configuração pode ser usada em conjunto com o atributo advClick. Se este atributo não for especificado, assume-se que nenhum avanço automático ocorrerá. Leitura/Gravação long.

**Retorna:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```

Especifica o tempo, em milissegundos, após o qual a transição deve começar. Essa configuração pode ser usada em conjunto com o atributo advClick. Se este atributo não for especificado, assume-se que nenhum avanço automático ocorrerá. Leitura/Gravação long.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```

Especifica a velocidade de transição que será usada ao transitar do slide atual para o próximo. Leitura/Gravação [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Retorna:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```

Especifica a velocidade de transição que será usada ao transitar do slide atual para o próximo. Leitura/Gravação [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public abstract ITransitionValueBase getValue()
```

Valor da transição de apresentação. Somente leitura [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Retorna:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public abstract int getType()
```

Tipo de transição. Leitura/Gravação [TransitionType](../../com.aspose.slides/transitiontype).

**Retorna:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Tipo de transição. Leitura/Gravação [TransitionType](../../com.aspose.slides/transitiontype).

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```

Especifica se este som é ou não um som incorporado. Se este atributo for definido como true, a aplicação geradora será alertada para verificar o atributo name especificado para este som em sua lista de sons incorporados e pode então exibir um nome ou UI personalizados conforme necessário. Leitura/Gravação boolean.

**Retorna:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```

Especifica se este som é ou não um som incorporado. Se este atributo for definido como true, a aplicação geradora será alertada para verificar o atributo name especificado para este som em sua lista de sons incorporados e pode então exibir um nome ou UI personalizados conforme necessário. Leitura/Gravação boolean.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```

Especifica um nome legível por humanos para o som da transição. A propriedade \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) deve ser atribuída para obter ou definir o nome do som. Leitura/Gravação String.

**Retorna:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```

Especifica um nome legível por humanos para o som da transição. A propriedade \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) deve ser atribuída para obter ou definir o nome do som. Leitura/Gravação String.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public abstract int getDuration()
```

Obtém ou define a duração do efeito de transição do slide em milissegundos. Leitura/Gravação int.

--------------------

Corresponde ao atributo p14:dur do elemento p:transition no esquema PresentationML. Se não definido, a duração é determinada automaticamente com base na propriedade \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) e no tipo de transição.

**Retorna:**
int
### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)
```

Obtém ou define a duração do efeito de transição do slide em milissegundos. Leitura/Gravação int.

--------------------

Corresponde ao atributo p14:dur do elemento p:transition no esquema PresentationML. Se não definido, a duração é determinada automaticamente com base na propriedade \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) e no tipo de transição.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |