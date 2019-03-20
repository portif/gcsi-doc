Internet e Intranet
===================

Internet
--------

A conexão à internet será feita por meio da interface *enp0s3*, que
obterá o endereço IP automaticamente via DHCP. No Ubuntu 18.04, as
configurações de interfaces de rede fica salvas no arquivo
``/etc/netplan/*.yaml``. Exemplo:

.. literalinclude:: host/amazonas/etc/netplan/01-network-manager-all.yaml
   :linenos:
   :language: yaml
   :emphasize-lines: 5,7,10

Nas versões anteriores do Ubuntu, assim como no Debian, as configurações de
rede TCP/IP das interfaces de rede são feitas no arquivo ``/etc/network/interfaces``.

.. literalinclude:: host/amazonas/etc/network/interfaces
   :linenos:
   :emphasize-lines: 2,5,8,14
   :caption: Configuração do arquivo /etc/network/interfaces


Intranet
--------
