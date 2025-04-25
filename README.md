
# UP REPO DEBIAN 10
<pre><code>apt update -y && apt upgrade -y && apt dist-upgrade -y && reboot</code></pre>

# UP REPO UBUNTU 20
<pre><code>apt update && apt upgrade -y && update-grub && sleep 2 && reboot</pre></code>

### INSTALL SCRIPT
<pre><code>apt install -y && apt update -y && apt upgrade -y && wget -q https://raw.githubusercontent.com/traderabal2/potato/main/main.sh && chmod +x main.sh && ./main.sh
</pre></code>

### UPDATE SCRIPT 
<pre><code>wget -q https://raw.githubusercontent.com/traderabal2/potato/main/update.sh && chmod +x update.sh && ./update.sh
</pre></code>
