# ansible-playbook-simple

This playbook uses the `debug` module to print a message.

To run this playbook:

    ansible-playbook -i hosts site.yml

To run it with a different variable, set the var called `person`:

    ansible-playbook -i hosts --extra-vars "person=Dave" site.yml

