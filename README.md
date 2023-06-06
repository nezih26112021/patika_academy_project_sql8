# patika_academy_project_sql8
query scenarios

Perform the following query scenarios on the "test" sample database.

1. Let's create a table named "employee" in your "test" database with column information id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100):

CREATE TABLE employee (

	id INTEGER, 
  
	name VARCHAR(50),
  
	birthday DATE,
  
	email VARCHAR(100)

);

2. Let's add 50 pieces of data to the employee table we created using the 'Mockaroo' service:

insert into employee (id, name, birthday, email) values (1, 'Sid', '1971-06-13', 'setienne0@instagram.com');
insert into employee (id, name, birthday, email) values (2, 'Leeann', '1953-05-13', 'lbotly1@bizjournals.com');
insert into employee (id, name, birthday, email) values (3, 'Armin', '1957-08-19', 'agoodlett2@fema.gov');
insert into employee (id, name, birthday, email) values (4, 'Templeton', '1962-03-08', 'tbowerman3@jugem.jp');
insert into employee (id, name, birthday, email) values (5, 'Giffer', '1979-11-05', 'gmctavy4@va.gov');
insert into employee (id, name, birthday, email) values (6, 'Freddy', '1956-06-07', 'fbrunger5@statcounter.com');
insert into employee (id, name, birthday, email) values (7, 'Alanna', '1987-06-08', 'akorn6@umich.edu');
insert into employee (id, name, birthday, email) values (8, 'Gaye', '1969-09-17', 'gsivil7@goo.ne.jp');
insert into employee (id, name, birthday, email) values (9, 'Kristo', '1982-01-06', 'kchawkley8@sphinn.com');
insert into employee (id, name, birthday, email) values (10, 'Sharon', '1973-10-15', 'ssparway9@taobao.com');
insert into employee (id, name, birthday, email) values (11, 'Chaddy', '1972-03-15', 'carundalea@wordpress.com');
insert into employee (id, name, birthday, email) values (12, 'Elise', '1959-03-01', 'ebreslaneb@yolasite.com');
insert into employee (id, name, birthday, email) values (13, 'Englebert', '1979-09-30', 'ekyngdonc@washingtonpost.com');
insert into employee (id, name, birthday, email) values (14, 'Harriette', '1961-10-25', 'hlyddond@reuters.com');
insert into employee (id, name, birthday, email) values (15, 'Bennie', '1961-02-24', 'bcleevese@scribd.com');
insert into employee (id, name, birthday, email) values (16, 'Geoffrey', '1950-07-19', 'gsabertonf@about.me');
insert into employee (id, name, birthday, email) values (17, 'Lexi', '1989-10-10', 'lgallyhaockg@multiply.com');
insert into employee (id, name, birthday, email) values (18, 'Ryan', '1975-11-19', 'rbotfieldh@blog.com');
insert into employee (id, name, birthday, email) values (19, 'Moises', '1979-04-15', 'mkosei@t.co');
insert into employee (id, name, birthday, email) values (20, 'Jacquette', '1962-06-27', 'jflutej@live.com');
insert into employee (id, name, birthday, email) values (21, 'Demetri', '1951-02-03', 'dabryk@example.com');
insert into employee (id, name, birthday, email) values (22, 'Thatch', '1980-02-14', 'tiddonsl@skype.com');
insert into employee (id, name, birthday, email) values (23, 'Pip', '1956-12-25', 'ppohlingm@posterous.com');
insert into employee (id, name, birthday, email) values (24, 'Julietta', '1981-05-12', 'jdrysdalln@cocolog-nifty.com');
insert into employee (id, name, birthday, email) values (25, 'Kira', '1954-08-28', 'kmcgaffeyo@meetup.com');
insert into employee (id, name, birthday, email) values (26, 'Eward', '1980-02-05', 'epennockp@smugmug.com');
insert into employee (id, name, birthday, email) values (27, 'Sean', '1959-09-03', 'sgreneq@un.org');
insert into employee (id, name, birthday, email) values (28, 'Lenore', '1952-12-18', 'llaner@posterous.com');
insert into employee (id, name, birthday, email) values (29, 'Blondy', '1957-02-23', 'bgebbs@yale.edu');
insert into employee (id, name, birthday, email) values (30, 'Harry', '1988-05-21', 'horrint@merriam-webster.com');
insert into employee (id, name, birthday, email) values (31, 'Dyanne', '1974-08-21', 'dshevelinu@si.edu');
insert into employee (id, name, birthday, email) values (32, 'Rhonda', '1983-12-31', 'rpawlikv@yandex.ru');
insert into employee (id, name, birthday, email) values (33, 'Blair', '1951-05-08', 'bhegdenw@google.it');
insert into employee (id, name, birthday, email) values (34, 'Oralla', '1966-07-29', 'omoizerx@miibeian.gov.cn');
insert into employee (id, name, birthday, email) values (35, 'Liam', '1990-05-18', 'ltherioty@soup.io');
insert into employee (id, name, birthday, email) values (36, 'Moise', '1964-02-12', 'mbrazurz@nasa.gov');
insert into employee (id, name, birthday, email) values (37, 'Chas', '1968-01-08', 'cchellam10@noaa.gov');
insert into employee (id, name, birthday, email) values (38, 'Ashley', '1953-09-07', 'abranston11@comsenz.com');
insert into employee (id, name, birthday, email) values (39, 'Deonne', '1961-02-25', 'dcalbreath12@princeton.edu');
insert into employee (id, name, birthday, email) values (40, 'Henrietta', '1964-03-13', 'hsolland13@businessinsider.com');
insert into employee (id, name, birthday, email) values (41, 'Melisent', '1981-09-05', 'mmchugh14@merriam-webster.com');
insert into employee (id, name, birthday, email) values (42, 'Dora', '1988-07-12', 'deakins15@scientificamerican.com');
insert into employee (id, name, birthday, email) values (43, 'Tiffani', '1974-04-01', 'tblesing16@1und1.de');
insert into employee (id, name, birthday, email) values (44, 'Anna', '1966-07-11', 'ashrimplin17@wiley.com');
insert into employee (id, name, birthday, email) values (45, 'Lea', '1987-10-04', 'lpymar18@godaddy.com');
insert into employee (id, name, birthday, email) values (46, 'Phillipp', '1971-12-04', 'phanhard19@smh.com.au');
insert into employee (id, name, birthday, email) values (47, 'Liam', '1967-09-04', 'lbingley1a@comcast.net');
insert into employee (id, name, birthday, email) values (48, 'Husein', '1954-02-15', 'hrau1b@arizona.edu');
insert into employee (id, name, birthday, email) values (49, 'Magdalen', '1961-01-06', 'myashin1c@cnet.com');
insert into employee (id, name, birthday, email) values (50, 'Erroll', '1969-03-02', 'eklimpke1d@w3.org');

3. Let's do 5 "UPDATE" operations that will update the other columns according to each of the columns:

UPDATE employee

	SET name='xxxx'
	
WHERE id=1;

4. Let's do 5 "DELETE" operations that will delete the relevant row according to each of the columns:

DELETE FROM employee

WHERE id=2;
