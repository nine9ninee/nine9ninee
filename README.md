
@@ -36,7 +36,7 @@ internal MainController()
                Icon = Resources.DeceiveIcon,
                Visible = true,
                BalloonTipTitle = StartupHandler.DeceiveTitle,
                BalloonTipText = "Deceive is currently masking your status. Right-Click the tray icon for more options."
                BalloonTipText = "Deceive is currently masking your status. Right-click the tray icon for more options."
            };
            _trayIcon.ShowBalloonTip(5000);

@@ -378,4 +378,4 @@ private void OnConnectionErrored()
            ConnectionErrored?.Invoke(this, EventArgs.Empty);
        }
    }
} 
}

