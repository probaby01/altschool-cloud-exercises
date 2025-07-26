# 🧪 10 Uncommon but Powerful Linux Commands

> These Linux tools are hidden gems for system monitoring, scripting, and productivity.

---

## 1. `tldr` — Simplified Command Manual

Shows community-simplified examples of command usage.

```bash
tldr tar
```

![tldr-example](images/tldr-example.png)

---

## 2. `ncdu` — Disk Usage Viewer with Navigation

Visual and navigable disk usage analyzer.

```bash
ncdu /
```

![ncdu-output](images/ncdu-output.png)

---

## 3. `htop` — Interactive Process Monitor (Better `top`)

Colorful, dynamic alternative to `top`.

```bash
htop
```

![htop-process-view](images/htop-process-view.png)

---

## 4. `bat` — Beautiful `cat` with Syntax Highlighting

Improves `cat` by adding colors and line numbers.

```bash
bat file.txt
```

![bat-preview](images/bat-preview.png)

---

## 5. `xargs` — Build & Execute Commands from Input

Pass multiple inputs to another command dynamically.

```bash
cat files.txt | xargs rm
```

![xargs-usage](images/xargs-usage.png)

---

## 6. `tree` — Visual Directory Tree

Displays folder structure in tree format.

```bash
tree /etc
```

![tree-command-output](images/tree-command-output.png)

---

## 7. `at` — Schedule One-Time Tasks

Run a command at a specific time (alternative to `cron`).

```bash
echo "shutdown -h now" | at 22:00
```

![at-command-schedule](images/at-command-schedule.png)

---

## 8. `watch` — Repeatedly Run a Command

Useful for monitoring output live.

```bash
watch -n 2 ls -lh
```

![watch-command-output](images/watch-command-output.png)

---

## 9. `ss` — Socket Statistics (Better `netstat`)

Faster and more detailed than `netstat`.

```bash
ss -tulwn
```

![ss-command-sockets](images/ss-command-sockets.png)

---

## 10. `dstat` — System Resource Overview

Shows CPU, disk, network, and memory stats in real time.

```bash
dstat
```

![dstat-realtime](images/dstat-realtime.png)

---

### 📦 Installation

Install these tools using your package manager:

```bash
sudo apt install tldr ncdu htop bat tree at dstat
```

Or use:

```bash
brew install tldr ncdu htop bat tree at dstat
```

---

### 📁 Directory Structure

```
.
├── README.md
└── images/
    ├── tldr-example.png
    ├── ncdu-output.png
    ├── htop-process-view.png
    ├── bat-preview.png
    ├── xargs-usage.png
    ├── tree-command-output.png
    ├── at-command-schedule.png
    ├── watch-command-output.png
    ├── ss-command-sockets.png
    └── dstat-realtime.png
```
