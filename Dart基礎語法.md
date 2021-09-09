# Dart 基礎語法
###  `main()` 或是 `void main()` 函式是Dart中的預定義方法。此方法充當應用程式的入口點。<br>Dart指令碼需要 `main()` 或是 `void main()` 方法來執行。
兩者打法差別只在嚴謹或不嚴謹

#### 不宣告型別語法實例
```Dart
main(){
var iWillBeInt  = 123; // Numbers 
var iWillBeString = "cxcxc"; //String
print(iWillBeInt.runtimeType);
print(iWillBeString.runtimeType);
}
```
#### 宣告型別語法實例
```Dart
void main(){
int iWillBeInt2 = 456;
String iWillBeString2 = "cxcxc-flutter";
print(iWillBeInt2.runtimeType);
print(iWillBeString2.runtimeType);
}
```
#### 不同型別的錯誤宣告實例
以下的打法，會跑出錯誤：
```Dart
void main(){
String actuallyBeInt = 123;
print(actuallyBeInt);
}
```
#### 字串相加實例
```Dart
void main(){
var iWillBeString = "cxcxc";
String iWillBeString2 = "cxcxc-flutter";
print( iWillBeString + iWillBeString2 );
}
```
#### 數字相加實例
```Dart
void main(){
var iWillBeInt  = 123;
int iWillBeInt2 = 456;
print( iWillBeInt +iWillBeInt2 );
}
```
