# Procedimentos Básicos de Rede

Este documento descreve procedimentos básicos para manutenção e verificação de uma rede de computadores.

---

## 1. Verificação de Conectividade de Rede

**Objetivo:**  
Garantir que os dispositivos estejam corretamente conectados à rede local e à internet.

**Procedimentos:**
1. Verificar se os cabos de rede estão corretamente conectados ao computador e ao switch/roteador.
2. Confirmar se o LED da porta de rede está aceso ou piscando.
3. Executar o comando `ping` para testar a comunicação com o gateway da rede.
4. Caso não haja resposta, reiniciar o equipamento de rede (roteador ou switch).

**Resultado Esperado:**  
O dispositivo deve responder ao teste de conectividade sem perda de pacotes.

---

## 2. Configuração de Endereço IP

**Objetivo:**  
Assegurar que o dispositivo possua um endereço IP válido na rede.

**Procedimentos:**
1. Verificar se o endereço IP está configurado como automático (DHCP).
2. Caso necessário, configurar manualmente:
   - Endereço IP
   - Máscara de rede
   - Gateway padrão
   - Servidor DNS
3. Reiniciar a interface de rede após a configuração.
4. Validar a configuração com o comando `ipconfig` ou `ifconfig`.

**Resultado Esperado:**  
O dispositivo deve receber um IP válido e acessar os recursos da rede.

---

## 3. Teste de Acesso a Serviços Internos

**Objetivo:**  
Confirmar o acesso a serviços internos da rede, c
