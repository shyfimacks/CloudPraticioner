# CloudPraticioner
Conjunto de anotações para a certificação AWS Cloud Practitioner	           
<h1>Cloud Computing</h1>
	
A computação em nuvem é a entrega de recursos de TI sob demanda por meio da Internet com definição de preço de pagamento conforme o uso. Em vez de comprar, ter e manter datacenters e servidores físicos, você pode acessar serviços de tecnologia, como capacidade computacional, armazenamento e bancos de dados, conforme a necessidade, usando um provedor de nuvem como a Amazon Web Services (AWS). 

<h2>Antes</h2> todas as empresas tinham seus proprios datacenters, e o principal problema era financeiro; os equipamentos são caros e a manutenção também; o tempo de montagem da infraestrutura também é grande; a empresa precisa investir também mão de obra qualificada para administrar os recursos. Todo o custo era repassado ao cliente.

<h2>Agora</h2> Com a computação em nuvem agora você não precisa se preocupar com o ambiente físico e pode acessar os seus serviços da onde quiser; não se preocupa com o tempo ocioso das máquinas e nem com a sobrecarga dos servidores.
	
<h3>Vantagens do Cloud computing</h3>
		<ul>
		<li>Velocidade</li>
		Velocidade para implementação de novas funcionalidades; deploy de serviços em tempo ágil; e habilitação rápida e solução de problemas rapidamente.
		<li>Updates</li>		
		Fica por conta da AWS, (Sem interromper o serviço); 
		<li>Custo</li>
		Redução de custo, fácil negociação relacionado a tempo e uso. Flexibilidade. Contratos flexiveis de 1,2,3 anos. Você troca despesas físicas por despesas variavéis
		<li>Data Security</li>
		Cloud já vende o serviço com sistema de backup garantido, você não se preocupa com a segurança dos dados.
		<li>Escalabilidade</li>
		Você consegue ter uma infraestutura dinâmica. Se precisar de mais recursos em ocasiões específicas isso é realizado automaticamente sem   indisponibilizar o ambiente.
		<ul>	
<a href="https://aws.amazon.com/pt/what-is-cloud-computing/">Material Complementar AWS</a>
	
<h2>Tipos de Cloud</h2>
		<ul>
		<li><b>IAAS</b></li>
				Você paga para utilizar a Infraestutura de alguém como serviço
				Exemplo: <a href="https://aws.amazon.com/pt/ec2/">EC2</a>
		<li><b>PAAS</b></li>
				Você paga para utilizar a plataforma como serviço
				Exemplo: <a href="https://aws.amazon.com/pt/s3/?trk=9c7f9c59-8d98-452d-8a14-441a9b6492f3&sc_channel=ps&s_kwcid=AL!4422!3!589951433465!e!!g!!s3&ef_id=CjwKCAjw1ICZBhAzEiwAFfvFhFc-g56IAxf7VIvF1-otvbXIYUPuWkgeZcnNjsn4DwfQa5j24GU05BoCRr8QAvD_BwE:G:s&s_kwcid=AL!4422!3!589951433465!e!!g!!s3">S3</a>, Elastic BeanStalk
		<li><b>SAAS</b></li>
				Você paga para utilizar o Software como serviço
				Exemplo: Rekognition, Polly, Translate.
			
![image](https://user-images.githubusercontent.com/103517751/189912426-de472787-1186-4667-bb0c-34a9a3adb9d8.png)
			
<h2>AWS SERVICES</h2>
Dominar o mundo!
Prover qualquer tipo de solução. Inciar, configurar e finalizar. Exemplo: EC2 é um serviço de virtualização, Route 53 é um serviço de DNS.

<a href="https://aws.amazon.com/pt/products/?aws-products-all.sort-by=item.additionalFields.productNameLowercase&aws-products-all.sort-order=asc&awsf.re%3AInvent=*all&awsf.Free%20Tier%20Type=*all&awsf.tech-category=*all)">Aws Services</a>
	
<h2>SHARED RESPONSABILITY MODEL - MODELO DE RESPONSABILIDADE COMPARTILHADA</h2>
<p>A AWS não vai conseguir manter a total segurança dos serviços oferecidos.<p>
			
<p>Responsabilidades  a AWS: Segurança DA cloud</p>
<p>Responsabilidades do Cliente: Segurança NA cloud <p>

<p>Responsabilidades  a AWS: Segurança DA cloud</p>
<p>Responsabilidades do Cliente: Segurança NA cloud <p>

<h2>CLI e CLOUDSHELL</h2>
<h3>Maneiras de acessar</h3>
<p>1.Console</p>
Na propria interface da AWS
<p>2.CLI</p>
Utilizando o terminal pessoal
<p>3.CLOUDSHELL</p>
Via Browser na conta AWS


<h2>Infraestrutura Global AWS</h2>

<p>A Nuvem AWS abrange 87 zonas de disponibilidade em 27 regiões geográficas em todo o mundo, com planos já divulgados para mais 21 zonas de disponibilidade e outras 7 regiões da AWS na Austrália, Canadá, Índia, Israel, Nova Zelândia, Espanha e Suíça.<p>
<p>245 países e territórios atendidos</p>
<p>115 locais do Direct Connect</p>
<p>17 zonas locais e 28 zonas Wavelenght</p>

<h2>Regiões da AWS</h2>
<p>Exemplo:USA=US-EAST-1,(País-area,regiao)</p>
			

<h2>Zonas de Disponibilidade</h2>
<p>Dentro da região existem os Datacenters, e estes são chamados de Zonas de Disponibilidade</p>
<p>Exemplo: Dentro da região US-EAST existem 3 zonas de disponibilidade: 2a, 2b e 2c, caso posteriormente fosse criado uma nova zona ela seguiria o mesmo padrão: 2d, 2e, etc. Por causa dalatência as zonas de disponibilidade não podem estar longes uma das outras, mas ao mesmo tempo não podem estar muito perto, pois são backups. 100kms normalmente separam as zonas de disponibilidade</p>

<h2>Zonas locais</h2>
<p>São datacenter menores, conectados nas zonas de Disponibilidades para que o usuário final possa estar mais próximo dos serviços.É ideal para conexões de Streaming por exemeplo</p>

<h2>Wavelenght</h2>
<p>São os equipamentos da AWS dentro das provedoras, para que a conexão final entre cliente e serviço seja facilitada</p>
			
<h2>AWS Outposts</h2>
<p>Nessa modalidade, a AWS aloca seus recursos e equipamentos dentro da empresa que deseja uma melhor conexão</p

<h1>AWS identify and Access Management (IAM)</h1>

<p>Com o AWS identify and Access Management (IAM), você pode especificar quem ou o que pode acessar serviços e recursos na AWS, gerenciar permissões refinadas de maneira centralizada e analisar o acesso para refinar permissões</p>

![image](https://user-images.githubusercontent.com/103517751/190635231-d4d85c15-4b91-45f2-9daf-c7820bcff47a.png)
<br>Todas as interações</br>

                                                                                                                                         
		
		
		
		
		
		
		
