# ansible-playbook for installing Anaconda

## using

- [ansible](http://www.ansible.com/)
- [Anaconda](https://www.continuum.io/downloads)
            
## target   
            
- ubuntu14.04
- ansible2#.1.1

## settings

- group_vars/all
    - target_user: vagrant  
        -> This user will be installing Anaconda
    - anacondascript: Anaconda3-4.1.1-Linux-x8664.sh  
        -> Anaconda installer

- hosts
    - test-server  
        -> This server will be install Anaconda 

