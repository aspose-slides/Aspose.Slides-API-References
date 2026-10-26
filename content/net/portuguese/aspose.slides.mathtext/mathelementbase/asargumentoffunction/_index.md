---
title: AsArgumentOfFunction
second_title: Referência da API Aspose.Sildes para .NET
description: Utiliza a função especificada usando esta instância como argumento
type: docs
weight: 20
url: /pt/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## AsArgumentOfFunction(IMathElement) {#asargumentoffunction}

Utiliza a função especificada usando esta instância como argumento

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| functionName | IMathElement | Nome da função |

### Valor de Retorno

Novo elemento matemático do tipo [`IMathFunction`](../../imathfunction)

### Exemplos

Exemplo:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Veja Também

* interface [IMathFunction](../../imathfunction)
* interface [IMathElement](../../imathelement)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(string) {#asargumentoffunction_4}

Utiliza a função especificada usando esta instância como argumento

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| functionName | String | Nome da função |

### Valor de Retorno

Novo elemento matemático do tipo [`IMathFunction`](../../imathfunction)

### Exemplos

Exemplo:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction("cos");
```

### Veja Também

* interface [IMathFunction](../../imathfunction)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

Utiliza a função especificada usando esta instância como argumento

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | Um dos tipos comuns de função de um argumento |

### Valor de Retorno

Novo elemento matemático do tipo [`IMathFunction`](../../imathfunction)

### Exemplos

Exemplo:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Veja Também

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

Utiliza a função especificada usando esta instância como argumento e o argumento adicional especificado

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Um dos tipos comuns de função de dois argumentos: Log, Lim, Min, Max |
| additionalArgument | IMathElement | Argumento adicional dependendo do tipo de função |

### Valor de Retorno

Novo elemento matemático do tipo [`IMathFunction`](../../imathfunction)

### Exemplos

Exemplo:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Retorna o logaritmo de 'x' na base '5'
```

### Veja Também

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* interface [IMathElement](../../imathelement)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

Utiliza a função especificada usando esta instância como argumento e o argumento adicional especificado

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Um dos tipos comuns de função de dois argumentos: Log, Lim, Min, Max |
| additionalArgument | String | Argumento adicional dependendo do tipo de função |

### Valor de Retorno

Novo elemento matemático do tipo [`IMathFunction`](../../imathfunction)

### Exemplos

Exemplo:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Retorna o logaritmo de 'x' na base '5'
```

### Veja Também

* interface [IMathFunction](../../imathfunction)
* enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->