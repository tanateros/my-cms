<h1>Installation</h1>
php composer.phar install
<h1>Requirements</h1>
PHP => 5.5
<br /><br />
CMF+CMS (2in1)

Желательный рефакторинг:
1) Полный рефакторинг динамической панели (убрать реализацию на Codeigniter 2.0.3, сделать согласно PSR и вообще вынести как отдельный модуль поставляемый через Composer)
2) Добавить контроль доступа используя ACL
3) Добавить сервис-контейнер (например Pimple)
4) Написать модуль для аналитики запросов и структуры БД (explain и правила нормализации таблиц)