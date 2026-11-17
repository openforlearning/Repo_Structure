# Repo_Structure
Overview of my continuously evolving Git Repo Structure to have a quick glance

#This is my Laptop (Acer Predator) :)
Mani Kumar@MyPredator UCRT64 ~/Documents/Learning/MyGithubRepos-New
$ cmd //c "tree /F"
Folder PATH listing
Volume serial number is 1432-8172
C:.
├───LearningProjects
│   ├───ansible-dynamic-inventory
│   │       ansible.cfg
│   │       frontend.aws_ec2.yaml
│   │       main.yaml
│   │
│   ├───ansible-import-include
│   │   │   inventory.ini
│   │   │   main.yaml
│   │   │
│   │   └───roles
│   │       ├───common
│   │       │   └───tasks
│   │       │           main.yaml
│   │       │
│   │       └───role-1
│   │           ├───tasks
│   │           │       main.yaml
│   │           │
│   │           └───vars
│   │                   main.yaml
│   │
│   ├───assignments
│   │       count-words.txt
│   │       data.csv
│   │       joindevops.com
│   │       joindevops.conf
│   │       joindevops.log
│   │       linux.md
│   │       shell-scripting.md
│   │
│   ├───concepts
│   │       .gitignore
│   │       01-devops-overview.md
│   │       02-why-cloud-migration.md
│   │       03-what-is-a-computer.md
│   │       04-linux.md
│   │       05-linux-commands.md
│   │       06-linux-admin.md
│   │       07-3-tier.md
│   │       08-dns.md
│   │       09-databases.md
│   │       10-backend.md
│   │       11-nginx.md
│   │       12-disk-management.md
│   │       13-shell-scripting.md
│   │       14-aws-cli.md
│   │       15-ansible.md
│   │       15-sending-gmail.md
│   │       README.md
│   │
│   ├───diagrams
│   │       3tier.drawio
│   │       ansible.drawio
│   │       aws-cli.drawio
│   │       client-server.drawio
│   │       dns.drawio
│   │       git.drawio
│   │       inode.drawio
│   │       piping.drawio
│   │       proxy.drawio
│   │       public-vs-private.drawio
│   │       redis.drawio
│   │       sg.drawio
│   │       shell-common.drawio
│   │       ssh-keys.drawio
│   │       terraform.drawio
│   │       vim.drawio
│   │
│   ├───expense-documentation
│   │   │   .gitignore
│   │   │   01-mysql.md
│   │   │   02-backend.md
│   │   │   03-frontend.md
│   │   │   04-lb.md
│   │   │   05-http-status-codes.md
│   │   │   backend-api.md
│   │   │   expense.conf
│   │   │   lb.conf
│   │   │   three-tier-arch.jpg
│   │   │
│   │   └───artifacts
│   │           expense-backend-v3.tar.gz
│   │           expense-backend-v4.tar.gz
│   │           expense-backend-v5.tar.gz
│   │           expense-frontend-v3.tar.gz
│   │           expense-frontend-v5.tar.gz
│   │
│   ├───learn-ansible
│   │       01-playbook.yaml
│   │       02-playbook.yaml
│   │       03-multi-play.yaml
│   │       04-nginx.yaml
│   │       05-variables.yaml
│   │       06-variables.yaml
│   │       07-variables.yaml
│   │       08-variables.yaml
│   │       09-variables.yaml
│   │       10-variables.yaml
│   │       11-vars-preference.yaml
│   │       12-gather-facts.yaml
│   │       13-data-types.yaml
│   │       14-conditions.yaml
│   │       15-conditions.yaml
│   │       16-loops.yaml
│   │       17-loops.yaml
│   │       18-loops.yaml
│   │       19-filter.yaml
│   │       20-error-handling.yaml
│   │       21-idempotency.yaml
│   │       22-shell-commad.yaml
│   │       23-secrets.yaml
│   │       ansible.cfg
│   │       course.yaml
│   │       facts.json
│   │       inventory.ini
│   │       student.json
│   │       student.xml
│   │       student.yaml
│   │
│   ├───learn-shell
│   │       01-hello-world.sh
│   │       02-conversation.sh
│   │       03-variables.sh
│   │       04-variables.sh
│   │       05-variables.sh
│   │       06-variables.sh
│   │       07-special-vars.sh
│   │       08-env-variable.sh
│   │       09-data-types.sh
│   │       10-condition.sh
│   │       11-conditions.sh
│   │       12-funtions.sh
│   │       13-logs.sh
│   │       14-loops.sh
│   │       15-loops.sh
│   │       16-loops.sh
│   │       17-colors.sh
│   │       18-set.sh
│   │       19-set.sh
│   │       20-script-1.sh
│   │       21-script-2.sh
│   │       22-while-loop.sh
│   │       23-cleanup.sh
│   │       24-archieve.sh
│   │       25-disk-usage.sh
│   │       mail.sh
│   │       template.html
│   │
│   ├───learn-terraform
│   │   │   .gitignore
│   │   │
│   │   ├───01-ec2
│   │   │       .terraform.lock.hcl
│   │   │       ec2.tf
│   │   │       provider.tf
│   │   │
│   │   └───02-variables
│   │           .terraform.lock.hcl
│   │           ec2.tf
│   │           provider.tf
│   │           variables.tf
│   │
│   ├───roboshop-ansible-v2
│   │   │   ansible.cfg
│   │   │   inventory.ini
│   │   │   main.yaml
│   │   │   roboshop.yaml
│   │   │
│   │   ├───group_vars
│   │   │   └───all
│   │   │           main.yaml
│   │   │           vault.yaml
│   │   │
│   │   └───roles
│   │       ├───cart
│   │       │   ├───tasks
│   │       │   │       main.yaml
│   │       │   │
│   │       │   └───templates
│   │       │           cart.service.j2
│   │       │
│   │       ├───catalogue
│   │       │   ├───defaults
│   │       │   │       main.yaml
│   │       │   │
│   │       │   ├───files
│   │       │   │       mongo.repo
│   │       │   │
│   │       │   ├───meta
│   │       │   │       main.yaml
│   │       │   │
│   │       │   ├───tasks
│   │       │   │       main.yaml
│   │       │   │
│   │       │   ├───templates
│   │       │   │       catalogue.service.j2
│   │       │   │
│   │       │   └───vars
│   │       │           main.yaml
│   │       │
│   │       ├───common
│   │       │   └───tasks
│   │       │           app-setup.yaml
│   │       │           java.yaml
│   │       │           main.yaml
│   │       │           nodejs.yaml
│   │       │           python.yaml
│   │       │           restart.yaml
│   │       │           systemd-setup.yaml
│   │       │
│   │       ├───example
│   │       │   └───tasks
│   │       │           main.yaml
│   │       │
│   │       ├───frontend
│   │       │   ├───handlers
│   │       │   │       main.yaml
│   │       │   │
│   │       │   ├───tasks
│   │       │   │       main.yaml
│   │       │   │
│   │       │   └───templates
│   │       │           roboshop.conf.j2
│   │       │
│   │       ├───mongodb
│   │       │   ├───files
│   │       │   │       mongo.repo
│   │       │   │
│   │       │   └───tasks
│   │       │           main.yaml
│   │       │
│   │       ├───mysql
│   │       │   └───tasks
│   │       │           main.yaml
│   │       │
│   │       ├───mysql-data
│   │       │   └───tasks
│   │       │           main.yaml
│   │       │
│   │       ├───payment
│   │       │   ├───tasks
│   │       │   │       main.yaml
│   │       │   │
│   │       │   └───templates
│   │       │           payment.service.j2
│   │       │
│   │       ├───rabbitmq
│   │       │   ├───files
│   │       │   │       rabbitmq.repo
│   │       │   │
│   │       │   └───tasks
│   │       │           main.yaml
│   │       │
│   │       ├───redis
│   │       │   └───tasks
│   │       │           main.yaml
│   │       │
│   │       ├───shipping
│   │       │   ├───meta
│   │       │   │       main.yaml
│   │       │   │
│   │       │   ├───tasks
│   │       │   │       main.yaml
│   │       │   │
│   │       │   └───templates
│   │       │           shipping.service.j2
│   │       │
│   │       └───user
│   │           ├───tasks
│   │           │       main.yaml
│   │           │
│   │           └───templates
│   │                   user.service.j2
│   │
│   ├───roboshop-documentation
│   │   │   .gitignore
│   │   │   01-mongodb.md
│   │   │   02-redis.md
│   │   │   03-mysql.md
│   │   │   04-rabbitmq.md
│   │   │   05-catalogue.md
│   │   │   06-user.md
│   │   │   07-cart.md
│   │   │   08-shipping.md
│   │   │   09-payment.md
│   │   │   10-dispatch.md
│   │   │   11-frontend.md
│   │   │   readme.md
│   │   │   roboshop.conf
│   │   │   roboshop.jpg
│   │   │
│   │   └───artifacts
│   │           cart-v4.zip
│   │           catalogue-v4.zip
│   │           dispatch-v4.zip
│   │           frontend-v4.zip
│   │           payment-v4.zip
│   │           shipping-v4.zip
│   │           user-v4.zip
│   │
│   ├───running-notes
│   │       session-01.txt
│   │       session-02.txt
│   │       session-03.txt
│   │       session-04.txt
│   │       session-05.txt
│   │       session-06.txt
│   │       session-07.txt
│   │       session-08.txt
│   │       session-09.txt
│   │       session-10.txt
│   │       session-11.txt
│   │       session-12.txt
│   │       session-13.txt
│   │       session-14.txt
│   │       session-15.txt
│   │       session-16.txt
│   │       session-17.txt
│   │       session-18.txt
│   │       session-19.txt
│   │       session-20.txt
│   │       session-21.txt
│   │       session-22.txt
│   │       session-23.txt
│   │       session-24.txt
│   │       session-25.txt
│   │       session-26.txt
│   │       session-27.txt
│   │       session-28.txt
│   │       session-29.txt
│   │       session-30.txt
│   │
│   ├───shell-roboshop-v1
│   │       01-mongodb.sh
│   │       02-redis.sh
│   │       03-mysql.sh
│   │       04-rabbitmq.sh
│   │       05-catalogue.sh
│   │       06-user.sh
│   │       07-cart.sh
│   │       08-shipping.sh
│   │       09-payment.sh
│   │       10-frontend.sh
│   │       cart.service
│   │       catalogue.service
│   │       mongo.repo
│   │       payment.service
│   │       rabbitmq.repo
│   │       roboshop-v1.sh
│   │       roboshop.conf
│   │       shipping.service
│   │       user.service
│   │
│   └───shell-roboshop-v2
│           01-mongodb.sh
│           02-redis.sh
│           03-mysql.sh
│           04-rabbitmq.sh
│           05-catalogue.sh
│           06-user.sh
│           07-cart.sh
│           08-shipping.sh
│           09-payment.sh
│           10-frontend.sh
│           cart.service
│           catalogue.service
│           common.sh
│           mongo.repo
│           payment.service
│           rabbitmq.repo
│           roboshop.conf
│           shipping.service
│           user.service
│
└───PersonalProjects
    ├───ansible_project
    │       .gitignore
    │       LICENSE
    │       README.md
    │
    ├───Roboshop-Docs
    │   └───roboshop-documentation
    │       │   .gitignore
    │       │   01-mongodb.md
    │       │   02-redis.md
    │       │   03-mysql.md
    │       │   04-rabbitmq.md
    │       │   05-catalogue.md
    │       │   06-user.md
    │       │   07-cart.md
    │       │   08-shipping.md
    │       │   09-payment.md
    │       │   10-dispatch.md
    │       │   11-frontend.md
    │       │   readme.md
    │       │   roboshop.conf
    │       │   roboshop.jpg
    │       │
    │       └───artifacts
    │               cart-v4.zip
    │               catalogue-v4.zip
    │               dispatch-v4.zip
    │               frontend-v4.zip
    │               payment-v4.zip
    │               shipping-v4.zip
    │               user-v4.zip
    │
    ├───Shell-Roboshop
    │       01-mongodb.sh
    │       02-redis.sh
    │       03-mysql.sh
    │       04-rabbitmq.sh
    │       05-catalogue.sh
    │       06-user.sh
    │       07-cart.sh
    │       08-shipping.sh
    │       09-payment.sh
    │       10-frontend.sh
    │       cart.service
    │       catalogue.service
    │       mongo.repo
    │       payment.service
    │       rabbitmq.repo
    │       README.md
    │       roboshop-v1.sh
    │       roboshop-v1b.sh
    │       roboshop-v1updated.sh
    │       roboshop.conf
    │       shipping.service
    │       user.service
    │
    ├───Shell_Scripting_Labs
    │       1-shell.sh
    │       10-evenodd.sh
    │       11-nestedifelse.sh
    │       12-conditions.sh
    │       13-validate.sh
    │       14-logredirection.sh
    │       15-simpleforloop.sh
    │       16-forloop.sh
    │       17-forloopimproved.sh
    │       18-forloopwithoutvalidatefunc.sh
    │       19-forloopenabledvalidatefuncandimproved.sh
    │       2-shell.sh
    │       20-colors.sh
    │       21-set.sh
    │       22-Whileloop.sh
    │       23-clearnup.sh
    │       24-archive.sh
    │       3-basicvar.sh
    │       4-variable.sh
    │       5-datevar.sh
    │       6-readvariable.sh
    │       7-readnhidevarinputs.sh
    │       8-specialvars.sh
    │       9-datatypes.sh
    │       README.md
    │
    └───society-management-app
        │   .gitignore
        │   LICENSE
        │   package-lock.json
        │   README.md
        │   updatedREADME.md
        │
        ├───backend
        │   │   .env
        │   │   index.js
        │   │   package-lock.json
        │   │   package.json
        │   │
        │   ├───config
        │   │       app.js
        │   │       db.js
        │   │
        │   ├───controllers
        │   │       paymentController.js
        │   │       residentController.js
        │   │       ticketController.js
        │   │
        │   └───routes
        │           paymentRoutes.js
        │           residentRoutes.js
        │           ticketRoutes.js
        │
        ├───docs
        │       01-mysql-mariadb.md
        │       02-backend.md
        │       03-frontend.md
        │       04-deployment.md
        │       05-artifacts.md
        │       06-artifacts-frontend.md
        │
        └───frontend
            │   package-lock.json
            │   package.json
            │   README.md
            │
            ├───build
            │   │   asset-manifest.json
            │   │   index.html
            │   │
            │   └───static
            │       ├───css
            │       │       main.b344d86d.css
            │       │       main.b344d86d.css.map
            │       │
            │       └───js
            │               main.58b6dbae.js
            │               main.58b6dbae.js.LICENSE.txt
            │               main.58b6dbae.js.map
            │
            ├───public
            │       index.html
            │
            └───src
                    App.js
                    index.js
