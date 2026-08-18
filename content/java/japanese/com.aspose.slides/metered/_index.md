---
title: Metered
second_title: Aspose.Slides for Java API リファレンス
description: メーターキーを設定するメソッドを提供します。
type: docs
url: /ja/com.aspose.slides/metered/
---
**継承:**  
java.lang.Object
```
public class Metered
```

メーターキーを設定するメソッドを提供します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Metered()](#Metered--) | このクラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | メーターの公開鍵と秘密鍵を設定します。 |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | 消費ファイルサイズを取得します |
| [getConsumptionCredit()](#getConsumptionCredit--) | 消費クレジットを取得します |
| [isMeteredLicensed()](#isMeteredLicensed--) | メーターがライセンスされているかどうかをチェックします |

### Metered() {#Metered--}
```
public Metered()
```

このクラスの新しいインスタンスを初期化します。

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```

メーターの公開鍵と秘密鍵を設定します。メーターライセンスを購入した場合、アプリケーションの起動時にこの API を呼び出す必要があります。通常はこれだけで十分です。ただし、消費データのアップロードが常に失敗し 24 時間を超えると、ライセンスが評価ステータスに設定されます。そのような事態を回避するために、ライセンスステータスを定期的に確認し、評価ステータスである場合は再度この API を呼び出すべきです。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| publicKey | java.lang.String | 公開鍵 |
| privateKey | java.lang.String | 秘密鍵 |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```

消費ファイルサイズを取得します

**戻り値:**
double

### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```

消費クレジットを取得します

**戻り値:**
double - 消費量

### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```

メーターがライセンスされているかどうかをチェックします

**戻り値:**
boolean - True or false