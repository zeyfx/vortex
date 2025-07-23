### Instalação

0.  Exclua a versão anterior (isso é uma recomendação, mas a decisão é sua).

1.  Instale o FL Studio.

2.  **Substitua** o conteúdo da pasta `24.2.2.4597_WD` pelo conteúdo da pasta de instalação do FL Studio, localizada em:

    ```
    C:\Program Files\Image-Line\FL Studio 2024
    ```

    **Observação:** Se você especificou um caminho de instalação diferente para o FL Studio (em outro disco), os arquivos devem ser substituídos nessa mesma pasta (no outro disco), e não na indicada acima.

3.  Execute o arquivo `FL Studio_24.2_reg_key.reg` e concorde em fazer as alterações.

4.  Abra o FL Studio, vá em "Unlock FL Studio" \> "Unlock with file". Clique no botão "More...", depois em "Save validation file..." e salve o arquivo `licensevalidation.txt` em um local de sua preferência. **Feche o FL Studio** (não minimize, saia do programa).

5.  Execute o `ID Patcher.exe` (que foi copiado para a pasta do programa). No campo "ID", copie o ID que está no arquivo `licensevalidation.txt` e clique em "Patch". Se o patcher exibir "Can't access to file. Patching FAILED\!\!\!", execute-o com direitos de administrador. Após usar o patcher, você pode excluí-lo.

    ► ASSISTIR VÍDEO

6.  **Substitua** o arquivo `engine_x64.dll` na seguinte pasta:

    ```
    C:\Program Files\Image-Line\FL Studio 2024\Plugins\Fruity\Generators\FLEX
    ```

    **Observação:** Se você especificou um caminho de instalação diferente para o FL Studio (em outro disco), os arquivos devem ser substituídos nessa mesma pasta (no outro disco), e não na indicada acima.

    **Importante\!** Se você baixar as bibliotecas FLEX Complete Expansion Bundle v2025.02, não é necessário seguir o passo \#6.

-----

### Observações Adicionais:

  * **Possibilidade de baixar online Edison Declipper, FL Cloud mastering, Stem extractor:** **SIM**. Se não conseguir baixá-los, você pode obtê-los **desta distribuição**.
  * **Possibilidade de baixar online o conjunto básico de bibliotecas para FLEX:** **NÃO**. Se precisar de bibliotecas, pegue-as **desta distribuição** ou do **FLEX Complete Expansion Bundle v2025.02**.
  * **FL Cloud:** **NÃO FUNCIONA**.

-----

### Opcional: Para alterar o nome no painel de dicas e na seção "Sobre" para o seu próprio.

No registro, localize a seguinte chave:

```
HKEY_CURRENT_USER\Software\Image-Line\Registrations
```

Altere o parâmetro `FL Studio license plate`. Seu valor padrão é `Lazy Witches`. Mude para o seu nome. Caracteres cirílicos são suportados.

Nas configurações do FL Studio, na aba **General**, na parte inferior, em "show license information in the hint panel", selecione **License plate** (embora esses parâmetros já venham definidos por padrão). Reinicie o FL Studio.
