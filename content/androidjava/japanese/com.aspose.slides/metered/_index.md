---
title: Metered
second_title: Java API リファレンスによる Aspose.Slides for Android
description: メータ付きキーを設定するメソッドを提供します。
type: docs
url: /ja/com.aspose.slides/metered/
---
**継承:**
java.lang.Object
```
public class Metered
```

メータ付きキーを設定するメソッドを提供します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Metered()](#Metered--) | このクラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | メータ付きの公開キーと秘密キーを設定します。 |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | 消費ファイルサイズを取得します |
| [getConsumptionCredit()](#getConsumptionCredit--) | 消費クレジットを取得します |
| [isMeteredLicensed()](#isMeteredLicensed--) | メータ付きがライセンスされているか確認します |
### Metered() {#Metered--}
```
public Metered()
```


このクラスの新しいインスタンスを初期化します。

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


メータ付きの公開キーと秘密キーを設定します。メータ付きライセンスを購入した場合、アプリケーション起動時にこの API を呼び出す必要があります。通常、これだけで十分です。ただし、消費データのアップロードが常に失敗し 24 時間を超えると、ライセンスは評価ステータスに設定されます。そのような事態を防ぐために、ライセンスステータスを定期的に確認し、評価ステータスであれば再度この API を呼び出す必要があります。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| publicKey | java.lang.String | 公開キー |
| privateKey | java.lang.String | 秘密キー |

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
double - consumption quantity
### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```


メータ付きがライセンスされているか確認します

**戻り値:**
boolean - True or false