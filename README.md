OOP
1. Основные термины ООП (объектно-ориентированного программирования) включают:

   - Класс: шаблон или формальное описание объекта, определяющий его состояние (переменные) и поведение (методы).
   - Объект: экземпляр класса, который имеет конкретные значения своих переменных и может выполнять определенные действия, вызывая свои методы.
   - Инкапсуляция: механизм, который объединяет данные и методы внутри класса, ограничивая прямой доступ к данным и обеспечивая контролируемый доступ через интерфейс.
   - Наследование: механизм, который позволяет создавать новый класс на основе существующего класса, наследуя его свойства и методы.
   - Полиморфизм: способность объектов с одним и тем же интерфейсом иметь разные реализации методов.

2. SOLID - это аббревиатура, расшифровывающая основные принципы объектно-ориентированного проектирования и программирования.Каждая буква в SOLID представляет один из следующих принципов:

   - S - Принцип единственной ответственности (Single Responsibility Principle): Каждый класс должен иметь только одну причину для изменения.
   - O - Принцип открытости/закрытости (Open/Closed Principle): Классы должны быть открыты для расширения, но закрыты для модификации.
   - L - Принцип подстановки Барбары Лисков (Liskov Substitution Principle): Объекты базового класса могут быть заменены объектами его подклассов без нарушения корректности программы.
   - I - Принцип разделения интерфейса (Interface Segregation Principle): Много маленьких специализированных интерфейсов лучше, чем один общий интерфейс.
   - D - Принцип инверсии зависимостей (Dependency Inversion Principle): Модули верхних уровней не должны зависеть от модулей нижних уровней. Оба типа модулей должны зависеть от абстракций.

3. Базовые паттерны проектирования:

   - Синглтон (Singleton): Гарантирует существование только одного экземпляра класса и предоставляет глобальную точку доступа к этому экземпляру.
   - Прокси (Proxy): Предоставляет заместитель или заполнитель для другого объекта, контролируя доступ к нему и добавляя дополнительное поведение.
   - Билдер (Builder): Позволяет создавать сложные объекты шаг за шагом, скрывая сложность конструирования и обеспечивая гибкость при создании различных вариантов объекта.
   - Фабрика (Factory): Предоставляет общий интерфейс для создания объектов, но позволяет подклассам решать, какой тип объекта создавать.
   - Декоратор (Decorator): Динамически добавляет новые функциональные возможности или изменяет поведение существующих объектов, не изменяя их базовой структуры.

4. Антипаттерны:

   - God object: Класс или объект, который содержит слишком много функциональности и становится сложным для понимания и поддержки.
   - Magic numbers: Жестко закодированные числовые значения в коде, которые трудно понять и поддерживать. Рекомендуется использовать именованные константы.
   - Процедурный стиль: Использование процедурного подхода к программированию, вместо объектно-ориентированного подхода. Это может приводить к сложному и неподдерживаемому коду.

5. Основные принципы проектирования:

   - KISS (Keep It Simple, Stupid): Простота - ключевой принцип в разработке. Код должен быть простым, легко понятным и поддерживаемым.
   - DRY (Don't Repeat Yourself): Избегайте дублирования кода. Логика должна быть вынесена в одно место и использоваться повторно при необходимости.
   - YAGNI (You Ain't Gonna Need It): Не пишите код для функциональности, которая в данный момент не требуется. Избегайте избыточности и лишних сложностей.

6. Основы парадигм программирования:

   - Императивное программирование: Описывает последовательность шагов, как достичь определенного результата. Фокусируется на изменении состояния и выполнении команд.
   - Декларативное программирование: Описывает желаемый результат, а не последовательность шагов для его достижения. Фокусируется на описании логики и правил, а не на управлении состоянием.
   
   Основные направления программирования включают ООП (объектно-ориентированное программирование), процедурное программирование, функциональное программирование, реактивное программирование и другие.

client-server

Архитектура клиент-сервер представляет собой распределенную модель, в которой клиентские устройства (например, компьютеры, мобильные устройства) обмениваются информацией и ресурсами с серверами. Основная идея заключается в том, что клиенты и серверы являются независимыми сущностями, которые взаимодействуют друг с другом посредством сетевых протоколов.

Основные компоненты архитектуры клиент-сервер:

1. Клиент: Это устройство или приложение, которое инициирует запросы к серверу для получения данных или выполнения определенных действий. Клиенты могут быть различными: веб-браузеры, мобильные приложения, настольные приложения и т. д.

2. Сервер: Это выделенное устройство или компьютер, которое предоставляет определенные услуги или ресурсы для клиентов. Сервер может быть специализированным (например, веб-сервер, база данных) или выполнять общие функции, такие как хранение и обработка данных.

3. Протоколы: Клиент и сервер взаимодействуют посредством сетевых протоколов, которые определяют правила обмена данных и коммуникации. Примеры популярных протоколов веб-архитектуры включают HTTP (Hypertext Transfer Protocol) и WebSocket.

Преимущества архитектуры клиент-сервер:

1. Распределение нагрузки: Клиенты и серверы могут быть масштабированы независимо друг от друга, что позволяет эффективно управлять нагрузкой на систему.

2. Централизованное управление: Сервер предоставляет централизованное управление ресурсами и обработкой данных, что упрощает администрирование и обеспечивает единообразие данных и бизнес-логики.

3. Разделение обязанностей: Архитектура клиент-сервер позволяет разделить обязанности между клиентскими и серверными компонентами, обеспечивая более четкую организацию кода и улучшая его поддержку и развитие.

4. Гибкость: Клиенты могут быть разработаны для разных платформ и устройств, что обеспечивает гибкость в выборе клиентской стороны, а серверы могут пред

оставлять различные услуги для разных клиентов.

Важно отметить, что архитектура клиент-сервер является одной из основных моделей в сетевой разработке, и в реальных приложениях она может быть дополнена другими компонентами и слоями, такими как прокси-серверы, балансировка нагрузки, кэширование и т. д., для обеспечения более сложного функционала и повышения производительности.
Вот несколько примеров применения архитектуры клиент-сервер:

1. Веб-приложение: Веб-приложения являются классическим примером использования клиент-серверной архитектуры. Клиент представляет собой веб-браузер, который отправляет запросы на сервер для получения веб-страниц, данных или выполнения действий. Сервер обрабатывает эти запросы и отправляет обратно клиенту необходимые данные или результаты действий.

2. Электронная почта: Клиентские почтовые программы, такие как Microsoft Outlook или Gmail, взаимодействуют с сервером по протоколам POP3 или IMAP для получения почтовых сообщений, и по протоколу SMTP для отправки сообщений. Сервер почты хранит и обрабатывает электронные письма, а клиентская программа обеспечивает интерфейс для работы с почтовыми ящиками.

3. Игровые приложения: Многопользовательские онлайн-игры используют архитектуру клиент-сервер для обмена информацией между игровым клиентом и игровым сервером. Клиент отправляет команды и получает обновления от сервера, который управляет игровой логикой и хранит данные о состоянии игры.

4. Мобильные приложения: Мобильные приложения также могут использовать клиент-серверную архитектуру для взаимодействия с удаленным сервером. Клиентское приложение на мобильном устройстве может отправлять запросы на сервер для получения данных, авторизации пользователя или выполнения других операций, в то время как сервер обрабатывает эти запросы и предоставляет необходимую информацию или функционал.

Это лишь некоторые примеры применения архитектуры клиент-сервер, и она широко используется во множестве различных типов приложений и систем, где требуется обмен данных и ресурсов между клиентами и серверами.

Security

1. Симметричное шифрование: Это метод шифрования, при котором используется один и тот же ключ для шифрования и расшифрования данных. Как только данные зашифрованы с использованием секретного ключа, для их расшифровки требуется тот же ключ. Примеры алгоритмов симметричного шифрования включают AES (Advanced Encryption Standard) и DES (Data Encryption Standard).

2. Асимметричное шифрование: Это метод шифрования, при котором используется пара ключей: публичный ключ для шифрования данных и приватный ключ для их расшифровки. Публичный ключ может быть распространен и доступен для всех, в то время как приватный ключ должен оставаться в тайне. Примеры алгоритмов асимметричного шифрования включают RSA и ECC (Elliptic Curve Cryptography).

3. SSL (Secure Sockets Layer): Это протокол безопасного соединения, который обеспечивает защищенную связь между клиентом и сервером через использование шифрования. SSL используется для обеспечения конфиденциальности и целостности передаваемых данных. В настоящее время SSL заменен на протокол TLS (Transport Layer Security).

4. Аутентификация: Это процесс проверки подлинности пользователя или системы. Он подтверждает идентичность субъекта путем проверки предоставленных учетных данных, таких как логин и пароль.

   Авторизация: Это процесс предоставления доступа авторизованным пользователям или системам к определенным ресурсам или функциям. Она определяет права и привилегии, которые имеет пользователь после успешной аутентификации.

   Идентификация: Это процесс установления идентичности субъекта, например, пользователя или устройства. Она может быть основана на уникальных идентификаторах, таких как имя пользователя или номер устройства.

5. SQL/XSS/XXE инъекции: Это типы атак на приложения, которые могут возникать при неправильной обработке пользовательского ввода. SQL-инъекция позволяет злоумышленнику выполнить вредоносный SQL-код в базе данных, XSS-инъекция позволяет внедрить вредоносный JavaScript-код на веб-страницу, а XXE-инъекция позволяет злоумышленнику выполнить атаки, используя расширенный XML-синтаксис. Чтобы предотвратить такие инъекции, необходимо

 правильно валидировать и экранировать пользовательский ввод и использовать параметризованные запросы или предварительно подготовленные выражения при работе с базой данных.

6. Защита от MITM (Man-in-the-Middle): MITM-атака возникает, когда злоумышленник встраивается между двумя коммуницирующими сторонами и перехватывает их коммуникацию. Чтобы защититься от MITM, необходимо использовать безопасные протоколы связи, такие как HTTPS, которые обеспечивают шифрование данных между клиентом и сервером. Также важно использовать сертификаты SSL/TLS от надежных удостоверяющих центров и следить за предупреждениями безопасности браузера о небезопасных соединениях.

Приведу примеры на Node.js:

1. Пример использования симметричного шифрования в Node.js с использованием модуля `crypto`:

```javascript
const crypto = require('crypto');

const algorithm = 'aes-256-cbc';
const key = 'mySecretKey';
const iv = crypto.randomBytes(16);

const encrypt = (text) => {
  const cipher = crypto.createCipheriv(algorithm, key, iv);
  let encrypted = cipher.update(text, 'utf8', 'hex');
  encrypted += cipher.final('hex');
  return encrypted;
};

const decrypt = (encrypted) => {
  const decipher = crypto.createDecipheriv(algorithm, key, iv);
  let decrypted = decipher.update(encrypted, 'hex', 'utf8');
  decrypted += decipher.final('utf8');
  return decrypted;
};

const plainText = 'Hello, world!';
const encryptedText = encrypt(plainText);
const decryptedText = decrypt(encryptedText);

console.log('Encrypted:', encryptedText);
console.log('Decrypted:', decryptedText);
```

2. Пример использования модуля `tls` для создания защищенного SSL/TLS-соединения на сервере:

```javascript
const tls = require('tls');
const fs = require('fs');

const options = {
  key: fs.readFileSync('private-key.pem'),
  cert: fs.readFileSync('public-cert.pem')
};

const server = tls.createServer(options, (socket) => {
  socket.write('Welcome to the secure server!');
  socket.end();
});

server.listen(8000, () => {
  console.log('Server is running on port 8000');
});
```

3. Пример использования модуля `express` для реализации аутентификации и авторизации в веб-приложении:

```javascript
const express = require('express');
const app = express();

// Аутентификация
app.post('/login', (req, res) => {
  // Проверка логина и пароля
  // Генерация и отправка токена аутентификации
});

// Авторизация
app.get('/protected', (req, res) => {
  // Проверка токена аутентификации
  // Предоставление доступа к защищенному ресурсу
});

app.listen(3000, () => {
  console.log('Server is running on port 3000');
});
```

4. Пример защиты от SQL-инъекций при использовании базы данных MySQL с использованием модуля `mysql`:

```javascript
const mysql = require('mysql');

const connection = mysql.createConnection({
  host: 'localhost',
  user: 'username',
  password: 'password',
  database: 'mydatabase'
});

const username = 'admin';
const password = "' OR 1=1 --";

const sql = `SELECT * FROM users WHERE username = '${username}' AND password = '${password}'`;

connection.query(sql, (error, results) => {
  if (error) throw error;
  console.log('Results:', results);
});

connection.end();
```

Обратите внимание, что в последнем примере использование параметризованных запросов или подготовленных выражений является предпочтительным для предотвращения SQL-инъекций, но данный пример показывает уязвимость без их использования.


GIT

- Git - это распределенная система контроля версий, которая позволяет управлять и отслеживать изменения в исходном коде и других файлах в течение времени.

- Commit (фиксация) - это операция, которая сохраняет изменения в репозитории. Коммит содержит снимок файлов в определенный момент времени, а также метаданные, такие как автор, дата и сообщение о коммите. Репозиторий - это место, где хранятся все коммиты и история изменений.

- Базовое устройство Git:
  - Working directory (рабочий каталог) - это место, где вы работаете с файлами проекта.
  - Staging area (промежуточная зона) - это область, где вы выбираете, какие изменения в файлах должны быть включены в следующий коммит.
  - Repository (репозиторий) - это место, где хранится история изменений, коммиты и другая информация о проекте.

- Работа с ветками:
  - Создание, удаление, переименование - для создания новой ветки используется команда `git branch <branch_name>`, для удаления ветки - `git branch -d <branch_name>`, для переименования ветки - `git branch -m <new_branch_name>`.
  - Просмотр списка веток и переключение между ними - для просмотра списка веток используется команда `git branch`, а для переключения между ветками - `git checkout <branch_name>`.

- Конфигурирование Git:
  - .gitignore - это файл, который содержит список шаблонов файлов и папок, которые должны быть проигнорированы Git при выполнении операций.
  - git config - команда, которая позволяет установить или просмотреть конфигурационные параметры Git, такие как имя пользователя, адрес электронной почты и другие настройки.

- Базовые команды:
  - add - добавляет изменения файлов в staging area перед коммитом (`git add <file_name>`).
  - commit - фиксирует изменения в репозитории (`git commit -m "Commit message"`).
  - push - отправляет локальные коммиты в удаленный репозиторий (`git push <remote_name> <branch_name>`).
  - fetch - получает изменения из удаленного репозитория без автоматического слияния (`git fetch <remote_name>`).
  - merge - объединяет изменения из одной ветки в другую (`git merge <branch_name>`).
  - pull - получает изменения из удаленного репозитория и автоматически объединяет их

 с текущей веткой (`git pull <remote_name> <branch_name>`).
  - stash - сохраняет текущие изменения в отдельном временном хранилище (`git stash`).

- Merge request (pull request) - это механизм сотрудничества в Git, который позволяет предложить изменения из одной ветки в другую. Он используется в системах управления версиями, таких как GitHub и GitLab, чтобы внести изменения в проект и запросить их рассмотрение и слияние.

- Навигация по истории - команда `git log` позволяет просмотреть историю коммитов в репозитории. Можно использовать различные опции, чтобы настроить вывод команды, например, `git log --oneline` покажет компактный список коммитов с их идентификаторами и сообщениями.

- Решение конфликтов - конфликты возникают, когда Git не может автоматически объединить изменения из разных веток. Решение конфликтов включает ручное редактирование файлов, чтобы выбрать нужные изменения. Конфликты помечены специальными маркерами в файлах, их нужно разрешить вручную, а затем выполнить коммит.
