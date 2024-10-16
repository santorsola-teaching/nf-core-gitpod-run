# Launching the RStudio environment

Once the nf-core pipeline run is terminated, you need to launch the RStudio server:

```bash
sudo rstudio-server start
```

A pop-up will appear and by clicking on **Open**, we will be redirected to the RStudio login page. By inserting the username and the password reported below, you will be able to connect to RStudio:

```bash
Username: gitpod
Password: pass
```

To prevent losing connection, go back to gitpod and type on the **Terminal**:

```bash
sleep 2h
```

This command will keep the gitpod session active for exactly 2 hours, providing sufficient time to complete our analysis without interruption.

