# azureNotes

Boot Diagnostics in Azure
"diagnosticsProfile": {
	"bootDiagnostics": {
	"enabled": true,
	"storageUri": "[concat('https://', parameters('newStorageAccountName'), '.blob.core.windows.net')]"
	}
    }
    }
}
