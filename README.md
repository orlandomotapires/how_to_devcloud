<h1 align="center">How to Intel® DevCloud Environment</h1>

<div align="center">
	<a href="https://www.intel.com/content/www/us/en/developer/tools/devcloud/overview.html">
	<img height = "250em" src = "https://github.com/orlandomotapires/how_to_devcloud/assets/80331486/76c2ac8c-520e-42e8-a90c-be8c5abd90bf" />
    </a>
</div>

## Written by 💻:

- [Fernando Schettini](https://linktr.ee/fernandoschett).
- [Orlando Mota Pires](https://github.com/orlandomotapires).

## Special thanks to 🥰:

- [Murilo Boratto](http://lattes.cnpq.br/9222855062709254), your experience and knowledge have been invaluable to our progress.
- [Ugonna Chikezie](https://www.linkedin.com/in/ugonnachikezie/), your experience and knowledge have been invaluable to our progress.

## About 🤔:

Here is a quick reference guide on how to utilize the execution queue within the Intel® DevCloud Environment. We'll provide some practical examples to demonstrate its usage and showcase a real-world example of submitting jobs.

----

## How to use the Intel® DevCloud Environment

### Creating your account:

Follow the [official Intel slides](./slides/IDC_Getting_Started-For_Developers.pdf) instructions.

### How to use Notebooks in DevCloud?

- Launch Jupyter Lab just like [official Intel slides](./slides/IDC_Getting_Started-For_Developers.pdf).
- Upload the [sample notebook](./codes/MM_sequential_parallel.ipynb) file into your Jupyter Lab files.
  
### How to launch an Compute Instance?

Follow the [official Intel slides](./slides/IDC_Getting_Started-For_Developers.pdf) instructions to launch your compute instance.

### How to SSH into your Compute Instance?

Inside the Terminal access the compute instance **[ EXAMPLE ]**:

    Host 146.152.*.*
    ProxyCommand /usr/bin/nc -x proxy-dmz.intel.com:1080 %h %p
    chmod 400 my-key.ssh
    ssh -J guest-dev8@10.165.57.24  6 ubuntu@172.16.1.118

----

## It is possible make a git clone on DevCloud?

Yes! Only in compute nodes **[ EXAMPLE ]**:

    git clone https://github.com/oneapi-src/oneAPI-samples.git

----

## How to contribute 🫂:

Feel free to create a new branch, fork the project, create a new Issue or make a pull request contact one of us to develop at how to devcloud guide.

## Licence 📜:

[Apache V2](https://choosealicense.com/licenses/apache-2.0/)