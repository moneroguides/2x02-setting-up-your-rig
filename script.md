# Setting Up Your Rig

<hr/>

### Intro

In the last episode we took an over view of mining and covered a few important things to think about before setting off.

Let's take a moment to recap.

First; The Monero protocol uses Proof-of-Work mining to achieve consensus. The algorithm, Random X is GPU and ASIC resistant, meaning the best hardware is also likely the best at general computing.
Second; Your reward for mining will be relative to the computing power of your CPU. Check out the [**Benchmark**](https://xmrig.com/benchmark) section of the XMRig website to see a ranked list. Don't aim for the scores you see here, you'll likely end up with around 80% of that score if done wisely.
Third; It's not particularly profitable to mine Monero. Aim to mine efficiently! Do not waste today what you can't guarantee tomorrow.
Finally; If you're going to join a pool. Join P2Pool!

As [Crypt0 Bear](https://youtube.com/watch?v=8xLbMQBkWhw) says 'Every hashrate, fucks a bank up'. Monero is for cypher punks, mining Monero keeps the dream alive and gives power to the social contract. 

Privacy is fundamental. [Monero means money](https://en.wiktionary.org/wiki/Monero).

<hr/>

### Setting up your Software

There are multiple ways to start mining Monero today. As a more advanced guide to our [quick start guide](https://moneroguides.org/tutorials/00x03-mining-monero-p2pool-quick-start-guide/) we're going to look at setting up the software in a fundamental way and as something you can set up as a (service)[https://moneroguides.org/tutorials/00x02-turning-your-monero-node-into-a-service/] as we have in previous videos.

We'll also take a moment here to pay tribute to (Gupax)[https://gupax.io/]. Unlike the official GUI, Gupax manages and installs XMrig and P2Pool directly and is a fantastic way to mine Monero. We strongly recommend checking out this software as an alternative to this series and there is already a great video guide on their website so we don't need to cover it here.

As discussed [XMRig](https://GitHub.com/xmrig) is the communities preferred solution to mining Monero. There are two options for installation and use; they are the pre-built binary files and building the the binaries yourself from the source code.

The binaries that are available here have a 1% donation fee hard coded into them. This 1% fee works by redirecting your hashing power periodically and pays for continued maintenance by the developers and the convenience of having these pre-built binaries. 

You may opt-out of this 1% donation if you prefer to contribute in a more direct way. This requires you to build the binaries from the source code; for which the developers offer a [detailed guide](https://xmrig.com/docs/miner/build).

In this video we'll be using the pre-built binaries.

After clicking on the [Binary releases](https://GitHub.com/xmrig/xmrig/releases) link you will find yourself presented with the latest version, clicking on the link will then take you to that version page.

Release notes can be found here at the top. They detail the changes made between the releases. Scrolling down you will find the sums for each binary and a signature file for those sums. All of which can be found in the Asset List.

Each binary is tailored to a different operating system; make sure you download the correct version. For demonstration purposes I'm using Ubuntu, Mac and Windows users should be able to follow along easily if you've already [gotten to grips with Monero](https://www.youtube.com/watch?v=AKB4w-L5ECA&list=PLcyDcJ4lpDVBpsnI-fbkB-7O4M63VIA2g).

A quick command in the terminal helps us identify our OS version. Windows users simply need the 'win64' version and Mac users only need to know the hardware architecture. 

<hr/>

### Setting up your Hardware

There are plenty of guides out there for how under-volt your CPU and modify your memory timings so we won't go into much detail on this topic. That being said, we do have some handy tips and hints for you to start with.

If you've chosen a CPU for mining, it's pretty likely that you have one from AMD's Ryzen family. Getting these CPUs running nice and efficiently takes a little bit of time and effort which will ultimately depend on a few factors. Those being your ambient air temperature and your chosen cooling solution.

In our experience, 0.92V is a great starting point for most Ryzen processors, how many clock cycles you'll get at this voltage will vary. Most modern CPUs should be fine with a staring Value of 3000 Mhz, keep cracking up the clock until it crashes, use XMRig for your stress test, after that, it's time for fine tuning. 

It's pretty important to know what the actually power consumption of your computer when it's mining. Although you can get values from most hardware monitoring software it's much better to understand how much power is being drawn from through the plug. We would recommend you invest in plugin type power meter, most modern ones can even track your electricity costs.


~moneroguides
