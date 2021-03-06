Если вы попали сюда случайно, то этот репозиторий вряд ли окажется вам полезен. Ну а если пришли целенаправленно --- читайте дальше :-)

### Предыстория

К вам, довольно известному специалисту по созданию стартапов, обратился директор аэропорта Домодедово. В последние годы ему не давала покоя мысль о том, что огромное количество мониторов, развешанных по всему аэропорту, не используют на полную катушку свой потенциал. Это мониторы круглые сутки показывают таблицы прилета-отлета, в то время как могли бы радовать людей и другой важной и полезной информацией.

После совместного мозгового штурма с командой топ-менеджеров аэропорта вы поняли: на мониторы нужно транслировать [пирожки](http://lurkmore.to/Пирожки). Это позволит радикально повысить лояльность клиентов и обеспечит благосклонное внимание СМИ.

Сказано --- сделано. С ходу сформулировали и требования к веб-приложению, отвечающему за показ пирожков на мониторах.

### Требования

Приложение должно показывать один пирожок, набранный крупным, хорошо читаемым шрифтом. Пирожок должен оставаться на экране 15 секунд, после чего должен меняться на другой, и так далее до бесконечности.

База пирожков должна пополняться из открытых источников (разумеется, с их владельцами будут заключены необходимые договоры):

* http://www.perashki.ru
* http://pirozhki-ru.livejournal.com
* http://www.stishkipirozhki.ru

Пирожок должен выбираться из базы случайным образом, но более популярные (получившие больше голосов) пирожки должны показываться чаще.

Загрузка пирожков из источников должна производиться по расписанию.

У зарегистрированных пользователей (сотрудников аэропорта) должна быть возможность вручную добавить пирожок (у менеджмента тоже случаются творческие озарения, знаете ли).

Приложение должно быть реализовано на Django. 

На реализацию задуманного взяли 2 недели.

### Реализация

К сожалению, непосредственно перед стартом проекта вас срочно вызвали в штаб-квартиру Фейсбука для консультаций по переписыванию ряда сервисов с php на python. Реализацию пирожков пришлось передать вашему молодому, но многообещающему коллеге.

Коллега управился за неделю, как раз к вашему возвращению из США. Он был так любезен, что даже выложил приложение на [хостинг](http://antonz.pythonanywhere.com). Довольный собой, коллега с городостью вручил вам ключи от гит-репозитория и отбыл в Таиланд.

На следующий день вы открыли код, и почуствовали неладное. А между тем, подходит время сдачи проекта заказчику. Теперь ваша задача --- исправить проблемы в приложении и привести его в соответствие с требованиями.

Пожалуйста, оформите исправления патчем с прилагающимся кратким описанием обнаруженных проблем и внесенных изменений. Правьте все, что сочтете нужным --- не обязательно только функциональные баги, можно любые "кривые" и неудачные решения.

Если вдруг так случится, что проблем слишком много, и вам не хочется все их исправлять, то поправьте самые критичные, а остальные просто перечислите и вкратце предложите вариант решения.
