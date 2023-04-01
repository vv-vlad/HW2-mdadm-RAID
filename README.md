# Инструкции

* [Как начать Git](git_quick_start.md)
* [Как начать Vagrant](vagrant_quick_start.md)

## HW2-mdadm-RAID

Работа с mdadm - https://drive.google.com/file/d/1phsvBYkiRPVrDG0EXagy-TF4P5y9XOAX/view?usp=share_link  
Что нужно сделать?

    добавить в Vagrantfile еще дисков;
    сломать/починить raid;
    собрать R0/R5/R10 на выбор;
    прописать собранный рейд в конф, чтобы рейд собирался при загрузке;
    создать GPT раздел и 5 партиций.
    Доп. задание*
    Vagrantfile, который сразу собирает систему с подключенным рейдом и смонтированными разделами.  После перезагрузки стенда разделы должны автоматически примонтироваться.
