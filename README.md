## Отчет о тестировании OpenJDK11

**Краткое описание:**  
16.11.2020 было проведено:
1. Тестирование инструкции по установке OpenJDK11
2. Тестирование установки OpenJDK11
3. Тестирование совместимости OpenJDK11 с использованием KeyValidator
4. Тестирование валидности ключей

**На тестирование затрачено: 4 часа.**  
В результате тестирования выявлены следующий дефект:
https://github.com/nmarenova/KeyValidator/issues/1

**В качестве тестовых данных использовались данные:**  
1. Инструкция по установке OpenJDK 11 https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md
 Ожидаемый результат - установился OpenJDK 11.
2. Руководство использования KeyValidator https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md
Ожидаемый результат - валидные ключи валидны, невалидные ключи не валидны.

**Тестирование производилось в следующем окружении:**  
Desktop, Windows 10, x64, java version "11.0.9" .

