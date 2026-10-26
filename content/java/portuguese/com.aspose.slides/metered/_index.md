---
title: Metered
second_title: Referência da API Aspose.Slides para Java
description: Fornece métodos para definir a chave metered.
type: docs
url: /pt/com.aspose.slides/metered/
---
**Herança:**
java.lang.Object
```
public class Metered
```

Fornece métodos para definir a chave metered.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [Metered()](#Metered--) | Inicializa uma nova instância desta classe. |
## Métodos

| Método | Descrição |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Define a chave pública e privada metered. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Obtém o tamanho do arquivo de consumo |
| [getConsumptionCredit()](#getConsumptionCredit--) | Obtém o crédito de consumo |
| [isMeteredLicensed()](#isMeteredLicensed--) | Verifica se o medidor está licenciado |
### Metered() {#Metered--}
```
public Metered()
```


Inicializa uma nova instância desta classe.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Define a chave pública e privada metered. Se você adquirir uma licença metered, ao iniciar a aplicação, esta API deve ser chamada; normalmente, isso é suficiente. No entanto, se falhar continuamente ao enviar dados de consumo e ultrapassar 24 horas, a licença será definida como status de avaliação; para evitar esse caso, você deve verificar regularmente o status da licença e, se estiver em status de avaliação, chamar esta API novamente.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| publicKey | java.lang.String | chave pública |
| privateKey | java.lang.String | chave privada |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Obtém o tamanho do arquivo de consumo

**Retorna:**
double
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Obtém o crédito de consumo

**Retorna:**
double - quantidade de consumo
### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```


Verifica se o medidor está licenciado

**Retorna:**
boolean - Verdadeiro ou falso