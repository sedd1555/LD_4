1.git push -u origin master
2.
3.
4.
5.Така система не потребу сервера, адже всі файли знаходяться по кожному з комп'ютерів.
Кожний з розробників працює зі своїм власним репозитарієм; Рішення щодо злиття гілок прийматься к исполнителю проекта; Немає потреби в мережевому з'єднанні;
не можливо контролювати доступ к файлам; відсутня загальна нумерация версій файлов; потрібно значно більше дискового просторука на сервере для зберігания всех гілок як глобальніх, так й локальних; відсутня можливість блокирование файлов.
специальный сервер, на который может быть загружена программа загрузки.
відповідає для контроля за производственными процесами, для мають загальну базу данных для управления и візуалізації
При внесении изменений в проект робоча копія на комп'ютері розробника старі, розбіжніїїї основною версією проекта збільшується. Это идеальный ризик виникнення конфліктних змін. Тому зручно підтримувати робочу копію в стані, максимально близкому до поточної основною версією, для чого робочу копії (обновление) наскільки можливо часто.
Завершивши черговий етап роботи над завданням, розробник фіксує (совершить) свои зміни, передаючи їх на сервере 
Разработчик модифицирующего проекта, змідні в нього файли в робочій копії відповідно до проектного завданням. 
програмний інструмент для керування версіями одиниці інформації
об'єднання незалежних змін в єдину версію документа.
Конфлікти можуть виникнути при операционной злиття, розгалужені від різних джерел. При зміненні одного и того ж рядка різними користувачами виникає конфлікт. Тобто якщо один користувач внес материалы в документ и виконає злиття - то конфлікту не буде. Але якщо після цього інший користувач змінить документ в тихих рядах, що і перший - то виникне конфлікт. Такому випадку конфліктівній вирішувати другий користувач (владелец, через своего виник конфлікт), или система (як правило, віпадку конфліктів покладається на користувачів).
Якщо у вас немає локальних змін, відбудеться само собою, як вироджений випадок на кшталт отримання останньої версії в централізованій системі управління версіями. Если у вас локальная среда, Git автоматически выполняет настройку, чтобы обеспечить возможность конфигурирования.
Ні
