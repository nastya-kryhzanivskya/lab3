# lab3
## Звіт до роботи

## Тема: Робота з бібліотекою NumPy

## Мета роботи: Попрактикуватись з бібліотекою NumPy, виконати завдання та завантажити їх у репозиторій

Виконання роботи

Результати виконання завдання знаходяться у файлі lab3.ipynb;
Встановила дану бібліотеку NumPy.
Створила новий файл lab3.ipynb та виконала в ньому завдання.
Для роботи з бібліотекою працювала інтерактивно в Jupytere Notebook.
Уважно переглянула код, постаралась зрозуміти чому виводиться саме такі значення.
Виконала код/приклади наведені в Notebook. Модифікувала Notebook та виконала наступні завдання:
Скрізь де є функція homework яка виводить повідомлення з позначкою >>>>> - виконала ці завдання!

Модифікувала код кожного print завдання та додайте пояснення чому виводиться саме такий результат.

Визначила за якою формулою генеруються значення для методу arange. Визначила формулу для методу linspace. Порівняла формули, для яких випадків вони можуть застосовуватись:

Метод arange генерує послідовність рівномірно розподілених чисел від початку до кінця заданого інтервалу. Формула для генерації таких чисел така: x = start + step * (i - 1)

Метод linspace генерує послідовність рівномірно розподілених чисел від початку до кінця заданого інтервалу, включаючи кінцевий елемент. Формула для генерації таких чисел така: x = start + (end - start) * (i / (num - 1))

Порівняння формул

Основна відмінність між формулами для методів arange та linspace полягає в тому, що метод arange включає початкове значення інтервалу в послідовність, а метод linspace - ні. Крім того, метод linspace дозволяє вказати кількість елементів послідовності, а метод arange - ні.

Застосування

Методи arange та linspace можна використовувати в різних випадках. Наприклад, вони можуть бути використані для створення послідовності чисел для графіка, для створення послідовності значень для ітераційного циклу або для створення послідовності значень для навчання моделі машинного навчання.

Створила декілька простих Векторів та Матриць та вивела їх розмірність. Виконала арифметичні операції над створеними Векторам/Матрицями;
import numpy as np

# Створення векторів
vector_a = np.array([1, 2, 3])
vector_b = np.array([4, 5, 6])

# Виведення розмірності векторів
print("Vector A shape:", vector_a.shape)
print("Vector B shape:", vector_b.shape)

# Створення матриць
matrix_A = np.array([[1, 2, 3], [4, 5, 6]])
matrix_B = np.array([[7, 8, 9], [10, 11, 12]])

# Виведення розмірності матриць
print("Matrix A shape:", matrix_A.shape)
print("Matrix B shape:", matrix_B.shape)

# Арифметичні операції
sum_vector = vector_a + vector_b
difference_vector = vector_a - vector_b
elementwise_product_vector = vector_a * vector_b
dot_product_vector = np.dot(vector_a, vector_b)

sum_matrix = matrix_A + matrix_B
difference_matrix = matrix_A - matrix_B
elementwise_product_matrix = matrix_A * matrix_B
matrix_product = np.dot(matrix_A, matrix_B.T)  # Транспонуємо матрицю B перед множенням

# Виведення результатів
print("\nVector Operations:")
print("Sum:", sum_vector)
print("Difference:", difference_vector)
print("Elementwise Product:", elementwise_product_vector)
print("Dot Product:", dot_product_vector)

print("\nMatrix Operations:")
print("Sum:\n", sum_matrix)
print("Difference:\n", difference_matrix)
print("Elementwise Product:\n", elementwise_product_matrix)
print("Matrix Product:\n", matrix_product)

Висновок: Попрактикувалась з бібліотекою NumPy, виконала завдання та завантажити їх у репозиторій
