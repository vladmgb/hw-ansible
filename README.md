# Домашнее задание к занятию 3 «Использование Ansible»


1. Допишите playbook: нужно сделать ещё один play, который устанавливает и настраивает LightHouse.

   [ссылка на playbook](https://github.com/vladmgb/hw-ansible/blob/main/playbook/site.yml)

3. При создании tasks рекомендую использовать модули: get_url, template, yum, apt.
   
4. Tasks должны: скачать статику LightHouse, установить Nginx или любой другой веб-сервер, настроить его конфиг для открытия LightHouse, запустить веб-сервер.
5. Подготовьте свой inventory-файл prod.yml.

ссылка на файл [prod.yml](https://github.com/vladmgb/hw-ansible/blob/main/playbook/inventory/prod.yml)
   
6. Запустите ansible-lint site.yml и исправьте ошибки, если они есть.

   Ошибки исправлены.

7. Попробуйте запустить playbook на этом окружении с флагом --check.

   Сделано.

   <img width="1065" height="522" alt="image" src="https://github.com/user-attachments/assets/0398f1fc-d888-4889-b93b-30abc588b8c7" />

   <img width="935" height="341" alt="image" src="https://github.com/user-attachments/assets/75d98a01-609c-4d85-872c-9103d5bf7220" />


8. Запустите playbook на prod.yml окружении с флагом --diff. Убедитесь, что изменения на системе произведены.

  Сделано.

  <img width="1071" height="530" alt="image" src="https://github.com/user-attachments/assets/3d502b77-890f-40e3-89b2-7e3693edff0c" />

    
9. Повторно запустите playbook с флагом --diff и убедитесь, что playbook идемпотентен.

  Сделано.
   
10. Подготовьте [README.md-файл](https://github.com/vladmgb/hw-ansible/edit/main/playbook/README.md) по своему playbook. В нём должно быть описано: что делает playbook, какие у него есть параметры и теги.
11. Готовый playbook выложите в свой репозиторий, поставьте тег 08-ansible-03-yandex на фиксирующий коммит, в ответ предоставьте ссылку на него.

[ссылка](https://github.com/vladmgb/hw-ansible.git)
