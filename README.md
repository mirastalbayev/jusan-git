# stepik-id-printer
Это проект для вывода моего персонального идентификатора на образовательной платформе stepik.org.
## Возможности
Данный проект имеет следующий функционал.
* Выводит в stdout уникальный идентификатор.
* Без зависимостей.
* Простой.
## Запуск
```
bash ./script.sh - выводит ваш id
bash ./username.sh - выводит ваше имя и фамилию
```
## Портирование
Данный проект можно портировать на другие языки программирования.
На Java
```Java
class Main {
    public static void main(String[] args) {
        System.out.println("777");
    }
}
```
На С++
```C++
#include <iostream>
using namespace std;
int main() {
    cout << 777 << endl;
    return 0;
}
```
> ![img](data:image/jpeg;base64,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) Попробуйте реализовать на Python, Go и JavaScript.
## Контакты разработчика
Ниже найдете список ссылок для связки с автором.
| Платформа | Ссылка                                               | Отвечу за |
| --------- |:----------------------------------------------------:| ---------:|
| Почта     | [Ссылка](https://github.com/mirastalbayev/jusan-git) | 24 часа   |
| LinkedIn  | [Ссылка](https://github.com/mirastalbayev/jusan-git) | 3 часа    |
| WhatsApp  | [Ссылка](https://github.com/mirastalbayev/jusan-git) | 30 минут  |
| Telegram  | [Ссылка](https://github.com/mirastalbayev/jusan-git) | 5 минут   |