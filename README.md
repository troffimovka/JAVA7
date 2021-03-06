# Instructions (C0 Coverage)
Это инструкции одиночного байтового кода Java. Покрытие инструкций предоставляет информацию об объеме кода, который был выполнен или пропущен. Эта метрика полностью независима от исходного форматирования и всегда доступна, даже при отсутствии отладочной информации в файлах классов.

# Branches (C1 Coverage)
Эта метрика подсчитывает общее количество ветвей в методе и определяет количество выполненных или пропущенных ветвей. Покрытие веток всегда доступно, даже при отсутствии отладочной информации в файлах классов. 

**Выделяются следующим образом:**

- Нет покрытия: нет ответвлений в линии (красный ромб)
- Частичное покрытие: выполнена только часть ветвей в линии (желтый ромб)
- Полное покрытие: все ответвления в линии выполнены (зеленый ромб)

# Lines
Можно рассчитать информацию о покрытии для отдельных строк. Исходная строка считается выполненной, если была выполнена хотя бы одна инструкция, назначенная этой строке.

Из-за того, что одна строка обычно компилируется в инструкции с многобайтовым кодом, выделение исходного кода показывает три разных состояния для каждой строки, содержащей исходный код:

- Нет покрытия: ни одна инструкция в строке не была выполнена (красный фон)
- Частичное покрытие: выполнена только часть инструкции в строке (желтый фон)
- Полное покрытие: все инструкции в строке выполнены (зеленый фон)


# Complexity
Вычисляет цикломатическую сложность для каждого неабстрактного метода и суммирует сложность для классов, пакетов и групп. Цикломатическая сложность - это минимальное количество путей, которые могут в (линейной) комбинации генерировать все возможные пути с помощью метода. Таким образом, значение сложности может служить индикатором количества примеров модульного тестирования, которые полностью охватывают определенную часть программного обеспечения. 
