# ansible-1

```bash
- 
  name: Test template playbook
  hosts: localhost
  vars: 
    my_name: Nitin Rajput
  tasks:
    - debug:
      msg: "My name is {{ my_name }}"
```
When you run the playbook , it should show the message with your name. If you not pass the value to the "my_name" variable it will create error.
